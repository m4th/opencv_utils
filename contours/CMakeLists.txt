cmake_minimum_required(VERSION 2.8)
project(contours_project)
find_package(OpenCV REQUIRED)
include_directories( ${OpenCV_INCLUDE_DIRS} )
add_executable(contours main.cpp)
target_link_libraries(contours ${OpenCV_LIBS})