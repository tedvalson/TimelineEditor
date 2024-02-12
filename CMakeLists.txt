cmake_minimum_required(VERSION 3.5)

project("TimelineEditor")

set(CMAKE_BUILD_TYPE Release CACHE STRING "Choose the type of build (Debug or Release)")
#option(BUILD_DOCS "Build doxygen documentation" OFF)

set(CMAKE_CXX_STANDARD 11)

add_subdirectory(src)
