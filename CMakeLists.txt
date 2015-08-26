cmake_minimum_required(VERSION 3.3)
project(Conway_ma_version)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    mon_conway/main.cpp)

add_executable(Conway_ma_version ${SOURCE_FILES})