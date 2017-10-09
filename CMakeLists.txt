cmake_minimum_required(VERSION 3.8)
project(TWMailer)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp myClient.cpp myServer.cpp)
add_executable(TWMailer ${SOURCE_FILES})