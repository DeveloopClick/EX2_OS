cmake_minimum_required(VERSION 3.16)
project(resources)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(resources
        demo_itimer.c
        demo_jmp.c
        demo_singInt_handler.c
        uthreads.cpp
        uthreads.h)
