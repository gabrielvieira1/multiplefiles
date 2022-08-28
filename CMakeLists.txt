cmake_minimum_required(VERSION 3.24)
project(multiplefiles C)

set(CMAKE_C_STANDARD 99)

add_executable(multiplefiles main.c main.h mapa.c mapa.h)
