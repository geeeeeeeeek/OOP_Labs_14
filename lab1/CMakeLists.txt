cmake_minimum_required(VERSION 3.3)
project(lab1)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES dictionary.cpp dict.cpp)
add_executable(lab1 ${SOURCE_FILES})