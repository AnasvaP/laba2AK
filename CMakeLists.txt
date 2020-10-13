cmake_minimum_required(VERSION 3.18.4 ) 

project("ProjectForAKl2" VERSION 0.1)
add_library(libraryCalc STATIC calculator.cpp)
add_executable("${PROJECT_NAME}" file1.cpp)
target_link_libraries("${PROJECT_NAME}" libraryCalc)		