cmake_minimum_required(VERSION 3.1)

set(OpenCV_DIR ${C//Users/KatePC/Desktop/opencv/build})
project(LR02.2)

find_package(OpenCV REQUIRED)

add_executable(LR02.2 src/Source.cpp)

target_link_libraries(LR02.2 ${OpenCV_LIBS})