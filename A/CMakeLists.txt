cmake_minimum_required(VERSION 3.0)
project(BuildSystems)

set(CMAKE_CXX_STANDARD 11)


set(SOURCES_LIST "lib.cpp")


add_library(lib ${SOURCES_LIST})

