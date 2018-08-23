cmake_minimum_required(VERSION 2.8)

project(extdemo1)

add_library(add STATIC add.h add.c)
add_library(sub STATIC sub.h sub.c)

add_executable(${PROJECT_NAME} "main.c")
