cmake_minimum_required(VERSION 3.7)
project(CPrimePlus)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c tree.h tree.c)
add_executable(CPrimePlus ${SOURCE_FILES})