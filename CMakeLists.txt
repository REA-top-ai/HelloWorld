cmake_minimum_required(VERSION 3.25)
project(HelloWorld 
        VERSION 1.0.0 
        LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
add_executable(hello_world main.cpp)