cmake_minimum_required(VERSION 3.3)
project(comp345Athena03102016_2)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    powerGrid/Cities.cpp
    powerGrid/Cities.h
    powerGrid/CMakeLists.txt
    powerGrid/Coal.cpp
    powerGrid/Coal.h
    powerGrid/Country.cpp
    powerGrid/Country.h
    powerGrid/GamePlay.cpp
    powerGrid/GamePlay.h
    powerGrid/Garbage.cpp
    powerGrid/Garbage.h
    powerGrid/Houses.cpp
    powerGrid/Houses.h
    powerGrid/main.cpp
    powerGrid/Money.cpp
    powerGrid/Money.h
    powerGrid/Oil.cpp
    powerGrid/Oil.h
    powerGrid/Payments.cpp
    powerGrid/Payments.h
    powerGrid/Player.cpp
    powerGrid/Player.h
    powerGrid/PlayerOrder.cpp
    powerGrid/PlayerOrder.h
    powerGrid/PowerPlant.cpp
    powerGrid/PowerPlant.h
    powerGrid/Resources.cpp
    powerGrid/Resources.h
    powerGrid/Uranium.cpp
    powerGrid/Uranium.h
    brownCities.txt
    powerPlant.dat
    zones.txt)

add_executable(comp345Athena03102016_2 ${SOURCE_FILES})