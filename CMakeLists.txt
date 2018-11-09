cmake_minimum_required(VERSION 3.12)
project(fft2)

set(CMAKE_CXX_STANDARD 17)
set(GCC_COVERAGE_COMPILE_FLAGS "-std=gnu++14 -I /usr/include/eigen3/ -pipe")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} ${GCC_COVERAGE_COMPILE_FLAGS}" )

add_executable(fft2 main.cpp)