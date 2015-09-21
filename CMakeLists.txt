cmake_minimum_required(VERSION 3.3)
project(boostdi_demo)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cc)
add_executable(boostdi_demo ${SOURCE_FILES})