cmake_minimum_required(VERSION 3.29)

project(GLAD)

add_library(glad STATIC src/glad.c include/glad/glad.h)
target_include_directories(glad PUBLIC include/)