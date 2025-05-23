cmake_minimum_required(VERSION 3.10)
project(MyProject)

# Set C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Include header files
include_directories(include)

# Gather all .cpp files in src/
file(GLOB SOURCES "src/*.cpp")

# Define the executable
add_executable(MyProject ${SOURCES})
