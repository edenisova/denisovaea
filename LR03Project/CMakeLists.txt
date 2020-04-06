cmake_minimum_required(VERSION 3.1)

set(OpenCV_DIR ${C//Users/KatePC/Desktop/opencv/build})
project(LR03)

find_package(OpenCV REQUIRED)

add_executable(LR03 src/Source.cpp)

target_link_libraries(LR03 ${OpenCV_LIBS})