cmake_minimum_required(VERSION 3.27)
project(CrystalDiskInfo)

set(CMAKE_CXX_STANDARD 14)

add_library(CrystalDiskInfo STATIC AtaSmart.cpp)