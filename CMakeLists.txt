##
## General CMake Settings
##
cmake_minimum_required(VERSION 3.10)

set(CMAKE_CXX_STANDARD 14)

##
## Project
##
project(ihmehimmeli)

##
## Include directories
##
include_directories(.)

##
## Subprojects
##
add_subdirectory(tempcoding)
add_subdirectory(abseil-cpp)
