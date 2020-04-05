cmake_minimum_required(VERSION 3.1)

set(OpenCV_DIR ${C//Users/KatePC/Desktop/opencv/build})
project(LR02.1)

find_package(OpenCV REQUIRED)

add_executable(LR02.1 src/Source.cpp)

target_link_libraries(LR02.1 ${OpenCV_LIBS})