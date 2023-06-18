cmake_minimum_required(VERSION 3.20)

project(serverz)

target_include_directories(./include)

set(SOURCE ./src/main.cpp)

add_executable(serverz ${SOURCE})