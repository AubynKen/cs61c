cmake_minimum_required(VERSION 3.19)
project(lab02 C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(lab02
        list.c
        list.h
        test_list.c)
