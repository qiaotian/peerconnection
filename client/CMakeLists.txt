cmake_minimum_required(VERSION 3.2.2)
project(client)

include_directories(${})

set(src_list main.cpp demo.cpp demo.h)
message(STATUS "This is Binary dir " ${CMakeDemo_BINARY_DIR})
message(STATUS "This is Source dir " ${CMakeDemo_SOURCE_DIR})
add_executable(client ${src_list})
