cmake_minimum_required(VERSION 3.20)
project(RayTracing)

set(CMAKE_CXX_STANDARD 23)

add_executable(RayTracing main.cpp vec3.h color.h ray.h)
