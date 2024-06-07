cmake_minimum_required(VERSION 3.28)
project(lox-c C)

set(CMAKE_C_STANDARD 99)

add_executable(lox-c src/main.c
        src/common.h
        src/chunk.h
        src/chunk.c
        src/memory.c
        src/memory.h
        src/debug.c
        src/debug.h
        src/value.c
        src/value.h
)
