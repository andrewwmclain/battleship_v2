cmake_minimum_required(VERSION 3.10)
project(Battleship)

set(CMAKE_CXX_STANDARD 14)

add_executable(Battleship main.cpp grid.cpp grid.h helpercode.cpp helpercode.h cpulogic.cpp cpulogic.h)