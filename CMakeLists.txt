cmake_minimum_required(VERSION 3.9)
project(LAB1D)

set(CMAKE_CXX_STANDARD 14)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/lab1)
add_executable(main lab1/main.cpp)