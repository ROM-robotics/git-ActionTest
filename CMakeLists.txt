cmake_minimum_required(VERSION 3.10)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# set the project name
project(example)

# add executable
add_executable(${PROJECT_NAME} example.cpp)

install(TARGETS ${PROJECT_NAME} DESTINATION bin)
#install(FILES example.h DESTINATION include)

