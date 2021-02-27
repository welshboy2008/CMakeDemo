cmake_minimum_required (VERSION 2.6)
include_directories(include)
set(CMAKE_CXX_COMPILER "g++-8")
project (demo LANGUAGES CXX)
set(CMAKE_CXX_COMPILER "/usr/local/bin/g++-8")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17")

add_executable (demo src/demo.cpp)
