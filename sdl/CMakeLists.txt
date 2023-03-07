cmake_minimum_required(VERSION 3.8)

project(sdl)

find_package(SDL2 REQUIRED)
include_directories(${SDL2_INCLUDE_DIRS})

add_executable(sdl main.cpp)
target_link_libraries(sdl ${SDL2_LIBRARIES})

