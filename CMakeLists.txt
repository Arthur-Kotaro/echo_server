cmake_minimum_required(VERSION 3.30)
project(echo_server)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(echo_server src/server_main.cpp)
add_executable(echo_client src/client_main.cpp)
include_directories(${CMAKE_CURRENT_SOURCE_DIR}/inc)


#add_library(echo_server server_main.hpp)
