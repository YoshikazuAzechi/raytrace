# root CMakeLists
cmake_minimum_required(VERSION 3.0.0)
project(RayTrace VERSION 0.1.0)

enable_language(CXX)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_subdirectory(source)