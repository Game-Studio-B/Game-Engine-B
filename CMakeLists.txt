cmake_minimum_required(VERSION 3.16)
project(Game_Engine_B)

set(CMAKE_CXX_STANDARD 14)

include_directories(src/headers)

add_executable(Game_Engine_B
        src/headers/geb_core.h
        src/geb_core.cpp)
