cmake_minimum_required(VERSION 2.8.7)

 project(Hello CXX)

 set(${PROJECT_NAME}_SRC
 src/main.cpp)

 add_executable(${PROJECT_NAME} ${${PROJECT_NAME}_SRC})
