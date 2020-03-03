cmake_minimum_required(VERSION 3.15)
project(Catch_TDD)

set(CMAKE_CXX_STANDARD 20)

set(SOURCE_FILES main.cpp)

add_executable(Catch_TDD_run ${SOURCE_FILES})

add_subdirectory(test)

include_directories(src)
add_subdirectory(src)