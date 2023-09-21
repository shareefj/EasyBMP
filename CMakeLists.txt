project(EasyBMP)
cmake_minimum_required(VERSION 3.18.4)

add_library(EasyBMP EasyBMP.cpp)
target_include_directories(EasyBMP PUBLIC ${CMAKE_CURRENT_LIST_DIR})