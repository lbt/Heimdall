cmake_minimum_required(VERSION 2.8.4)
project(libpit)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++11")

set(LIBPIT_SOURCE_FILES
    Source/libpit.cpp
    Source/libpit.h)

add_library(pit STATIC ${LIBPIT_SOURCE_FILES})
