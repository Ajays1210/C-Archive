cmake_minimum_required(VERSION 4.2)
project(Programs C)

set(CMAKE_C_STANDARD 99)
set(CMAKE_C_STANDARD_REQUIRED ON)

add_executable(helloWorld HelloWorld/helloWorld.c)
add_executable(printName PrintName/printName.c)
