cmake_minimum_required(VERSION 3.27.0)

set(CMAKE_BUILD_TYPE Debug )
set(CMAKE_CXX_FLAGS_RELEASE "-O3")
project(cache LANGUAGES CXX)

add_subdirectory(src)
