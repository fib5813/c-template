cmake_minimum_required(VERSION 2.8.3)
project(main)

set (CMAKE_CXX_STANDARD 11)
include_directories("${PROJECT_BINARY_DIR}")
 
add_executable(main main.cpp)

