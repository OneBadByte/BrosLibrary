cmake_minimum_required(VERSION 3.3)
project(BrosLibrary)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp BrosLibrary.h)
add_executable(BrosLibrary ${SOURCE_FILES})