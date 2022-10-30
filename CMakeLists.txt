cmake_minimum_required(VERSION 3.23)
project(pintos C)

set(CMAKE_C_STANDARD 99)
include_directories(src src/lib src/lib/kernel)
add_executable(pintos main.c)
