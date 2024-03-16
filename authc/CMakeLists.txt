cmake_minimum_required(VERSION 3.22)
project(authc)

set(CMAKE_CXX_STANDARD 14)

include_directories(src)

add_executable(authc
        src/crc.h
        src/main.cpp)
