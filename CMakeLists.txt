cmake_minimum_required(VERSION 3.10)

project(BMSUART)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)


set(SOURCES
    src/main.cpp
    src/bms_uart.cpp
)

add_executable(bms ${SOURCES})
include_directories(${CMAKE_SOURCE_DIR}/include)
