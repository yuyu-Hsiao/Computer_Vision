cmake_minimum_required(VERSION 3.0)
project(cv_hw4)

find_package(OpenCV REQUIRED)

add_executable(main main.cpp)
target_link_libraries(main ${OpenCV_LIBS})
