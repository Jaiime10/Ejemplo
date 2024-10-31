cmake_minimum_required(VERSION 3.29)
project(Ejemplo)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Ejemplo
    main.cpp
    main.h)
