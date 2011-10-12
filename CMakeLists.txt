cmake_minimum_required(VERSION 2.6)

project(Proj)

include_directories(${CMAKE_CURRENT_SOURCE_DIR}/include)
link_directories(${CMAKE_CURRENT_SOURCE_DIR}/library)

add_library(alib
    source/bmp.cc
    include/bmp.h
)

add_subdirectory(test)


