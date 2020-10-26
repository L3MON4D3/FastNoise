cmake_minimum_required(VERSION 3.13)
project(fastNoise CXX)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_library(fastNoise
    FastNoise.cpp
)

 target_include_directories(fastNoise PUBLIC ./)
