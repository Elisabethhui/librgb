#=============================================================================#
# Author: Konstantin Gredeskoul https://github.com/kigster                    #
# © 2017 All rights reserved, MIT License                                     #
#                                                                             #
# Description: Arduino CMake Top Level file that uses Arli Library Manager    #
# https://github.com/kigster/arli                                             #
#                                                                             #
# Depends on Arduino-CMake project found at                                   #
# https://github.com/arduino-cmake/arduino-cmake                              #
#                                                                             #
#=============================================================================#

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

cmake_minimum_required(VERSION 3.0)

project(librgb C CXX)

add_subdirectory(src)
add_subdirectory(test)

