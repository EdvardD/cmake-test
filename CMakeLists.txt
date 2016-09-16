cmake_minimum_required(VERSION 2.8.4)
project(A)

add_subdirectory(B1 B1)
add_subdirectory(B2 B2)

include_directories(B1 B2)

add_executable(A main.cpp)
target_link_libraries(A B1 B2)
