cmake_minimum_required(VERSION 3.28.3)
project(GameEngine)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_INCLUDE_CURRENT_DIR ON)

set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_DEPENDS_USE_COMPILER OFF)

add_executable(test main.cpp)