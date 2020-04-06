cmake_minimum_required(VERSION 3.1)

set(OpenCV_DIR ${C//Users/KatePC/Desktop/opencv/build})
project(LR01)

find_package(OpenCV REQUIRED)

add_executable(LR01 src/Source.cpp)

target_link_libraries(LR01 ${OpenCV_LIBS})