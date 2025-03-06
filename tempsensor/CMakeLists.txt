cmake_minimum_required(VERSION 3.6)
project(tempsensor LANGUAGES CXX)

set(CMAKE_RUNTIM_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/bin)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIERD ON)

add_subdirectory(src)
