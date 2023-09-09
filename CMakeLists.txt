cmake_minimum_required(VERSION 3.26)
project(Adafruit_PixelDust)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(raspberry_pi)

add_executable(Adafruit_PixelDust
        raspberry_pi/buttons.py
        raspberry_pi/cube.cpp
        raspberry_pi/demo1-snow.cpp
        raspberry_pi/demo2-hourglass.cpp
        raspberry_pi/demo3-logo.cpp
        raspberry_pi/lis3dh.cpp
        raspberry_pi/lis3dh.h
        raspberry_pi/logo.h
        raspberry_pi/Makefile
        Adafruit_PixelDust.cpp
        Adafruit_PixelDust.h)
