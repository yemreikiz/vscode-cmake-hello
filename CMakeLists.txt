#version 3.11 or later of Cmake needed for installing GoogleTest
cmake_minimum_required(VERSION 3.11-3.18)

project(
    VscodeCmakeHello
    VERSION 0.1
    DESCRIPTION "Small CMake example built with VSCode"
)

add_subdirectory(hello)

add_subdirectory(apps)
