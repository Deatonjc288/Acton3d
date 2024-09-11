cmake_minimum_required(VERSION 3.15)
project(Acton3d)

# Set C++ standard
set(CMAKE_CXX_STANDARD 17)

# Include directories
include_directories(${CMAKE_SOURCE_DIR}/libs)

# Add source files
file(GLOB_RECURSE ENGINE_SOURCES src/*.cpp src/*.c)

# Add executable
add_executable(Acton3d ${ENGINE_SOURCES})
