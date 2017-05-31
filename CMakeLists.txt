cmake_minimum_required(VERSION 3.7)
project(tinyrenderer)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        main.cpp
        Makefile
        tgaimage.cpp
        tgaimage.h)

add_executable(tinyrenderer ${SOURCE_FILES})