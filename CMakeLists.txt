cmake_minimum_required(VERSION 3.10)
project(problem_110)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(code main.cpp)

# Set output name to code
set_target_properties(code PROPERTIES
    RUNTIME_OUTPUT_NAME code
)