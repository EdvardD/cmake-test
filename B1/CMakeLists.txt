cmake_minimum_required(VERSION 2.8.4)
project(B1)

file(GLOB SOURCES "*.cpp")
add_library(B1 ${SOURCES})
