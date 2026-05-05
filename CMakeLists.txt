cmake_minimum_required(VERSION 3.22...4.2)

project(gfakluge
    LANGUAGES CXX
)

add_library(gfakluge STATIC
    src/main.cpp
)
target_include_directories(gfakluge PUBLIC 
    src/tinyFA
    src
)