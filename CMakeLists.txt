cmake_minimum_required(VERSION 3.10)

project(HelloCov)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} --coverage")

add_subdirectory(src)

enable_testing()
add_subdirectory(test)

