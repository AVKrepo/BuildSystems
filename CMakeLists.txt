cmake_minimum_required(VERSION 3.0)
project(BuildSystems)

set(CMAKE_CXX_STANDARD 11)


set(SOURCES_LIST B/main.cpp)

include_directories(".")
add_subdirectory("A")

add_executable(proj ${SOURCES_LIST})
target_link_libraries(proj lib)
