cmake_minimum_required(VERSION 3.7)
project(BasicCCompiler)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES frame.c)
add_executable(BasicCCompiler ${SOURCE_FILES})