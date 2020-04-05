# CMakeLists.txt

cmake_minimum_required(VERSION 3.9.5)
project(CMAKE_PALY)

message("Processing CMakeLists.txt")

include_directories(header)
add_library(libhello source/libhello.cpp)
add_executable(hello source/hello.cpp)
target_link_libraries(hello libhello)
