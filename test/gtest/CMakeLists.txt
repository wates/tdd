cmake_minimum_required(VERSION 2.6)

project(gtest)

set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR})
set(LIBRARY_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR})
add_library(gtest gtest-all.cc gtest_main.cc gtest.h)

