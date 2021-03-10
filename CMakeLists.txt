cmake_minimum_required(VERSION 3.12)
project(glad)

add_library(
    glad SHARED
    src/glad.c
)
add_library(
    gl::glad ALIAS glad
)

target_include_directories(glad PUBLIC include)
