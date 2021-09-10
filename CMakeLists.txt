cmake_minimum_required(VERSION 3.19)

project(add)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_library(add STATIC)

target_sources(add
PRIVATE
    add.c
    add.cpp
)
