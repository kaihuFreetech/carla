cmake_minimum_required(VERSION 3.9.0)
project(CARLA)

include("Build/CMakeLists.txt.in")

add_subdirectory("LibCarla/cmake")
