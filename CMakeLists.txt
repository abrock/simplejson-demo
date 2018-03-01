cmake_minimum_required(VERSION 2.8)

project(simplejson-demo)
add_executable(${PROJECT_NAME} "main.cpp")

add_library(someclass someclass.cpp)

target_link_libraries(${PROJECT_NAME} someclass)
