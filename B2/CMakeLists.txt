cmake_minimum_required(VERSION 2.8.4)
project(B2)

file(GLOB SOURCES "*.cpp")
add_library(B2 ${SOURCES})
