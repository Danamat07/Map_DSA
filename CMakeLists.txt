cmake_minimum_required(VERSION 3.27)
project(Map_fr)

set(CMAKE_CXX_STANDARD 17)

add_executable(Map_fr
        App.cpp
        ExtendedTest.cpp
        ExtendedTest.h
        Map.cpp
        Map.h
        MapIterator.cpp
        MapIterator.h
        ShortTest.cpp
        ShortTest.h)
