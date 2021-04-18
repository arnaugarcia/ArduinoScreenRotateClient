cmake_minimum_required(VERSION 3.19)
project(ArduinoScreenRotateClient)

set(CMAKE_CXX_STANDARD 20)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} ${GTK_CFLAGS} -framework IOKit -framework ApplicationServices")

add_executable(ArduinoScreenRotateClient main.cpp)
