# CMakeLists.txt
# basic CMake project
cmake_minimum_required(VERSION 3.5)

# project name
project(hello_cmake)

# add the executable
add_executable(hello_world src/main.cpp)

# set the C++ standard required
set(CMAKE_CXX_STANDARD_REQUIRED True)

# set the C++ standard
set(CMAKE_CXX_STANDARD 17)
