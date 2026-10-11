cmake_minimum_required(VERSION 3.10)

project(lua)

add_library(${PROJECT_NAME} STATIC onelua.c)
target_compile_definitions(${PROJECT_NAME} PRIVATE MAKE_LIB)