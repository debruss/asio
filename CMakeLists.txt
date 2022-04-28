cmake_minimum_required(VERSION 3.16)

project(Asio)

message(${INSTALL_PATH}/assets)
install(DIRECTORY ${CMAKE_CURRENT_LIST_DIR}/asio/ DESTINATION ${CMAKE_INSTALL_PREFIX}/include/asio)
install(FILES ${CMAKE_CURRENT_LIST_DIR}/asio.hpp DESTINATION ${CMAKE_INSTALL_PREFIX}/include/asio.hpp)
