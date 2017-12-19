cmake_minimum_required(VERSION 3.9)
project(unperformancelab4)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS "-fcilkplus -lcilkrts -Werror -Wfatal-errors -Wall")

add_executable(unperformancelab4 mm_loops.cpp mm_recursive.cpp)
