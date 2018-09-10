cmake_minimum_required(VERSION 3.8)
project(rotk)

set(CMAKE_CXX_STANDARD 17)
set(MY_SOURCE_DIR include)
include_directories( ${MY_SOURCE_DIR}/ )

add_executable(hive src/main.cpp)
