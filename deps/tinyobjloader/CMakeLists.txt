cmake_minimum_required(VERSION 3.20)
project(tinyobjloader)

add_library(tinyobjloader INTERFACE)
target_include_directories(tinyobjloader INTERFACE include "${CMAKE_CURRENT_SOURCE_DIR}/")