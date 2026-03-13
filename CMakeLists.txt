# CMakeLists.txt for Trailer Dimension Measurement Project

cmake_minimum_required(VERSION 3.10)

# Set the project name
project(TrailerDimensionMeasurement)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable
add_executable(TrailerDimenMeas src/main.cpp)

# Include directories
include_directories(include)