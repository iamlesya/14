cmake_minimum_required(VERSION 3.23)
project(untitled8 C)

set(CMAKE_C_STANDARD 99)

add_executable(untitled8 main.c)

add_subdirectory(libs)
target_link_libraries(untitled8 data_structures)