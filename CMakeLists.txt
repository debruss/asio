cmake_minimum_required(VERSION 3.16)

project(Asio)

message(${INSTALL_PATH}/assets)
install(DIRECTORY ${CMAKE_CURRENT_LIST_DIR} DESTINATION ${CMAKE_INSTALL_PREFIX}/include/asio
            FILES_MATCHING PATTERN "*.hpp")
