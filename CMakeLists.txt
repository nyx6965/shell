cmake_minimum_required(VERSION 3.10)
project(microshell)

set(CMAKE_C_STANDARD 11)

include_directories(include)

set(SOURCES
    src/main.c
    src/builtin.c
    src/utils.c
    src/parser.c
)

add_executable(microshell ${SOURCES})

