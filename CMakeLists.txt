cmake_minimum_required(VERSION 2.8.8 FATAL_ERROR)

project(DiabloDB)

set(CMAKE_CXX_COMPILER "g++")
set(CMAKE_CXX_FLAGS_DEBUG "-g3 -Wall")
set(CMAKE_CXX_FLAGS_RELEASE "-O2 -Wall")

add_subdirectory(src)


