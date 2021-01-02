# CMake最低版本号要求
cmake_minimum_required(VERSION 3.5)

project(code_study_for_cpp LANGUAGES CXX)

# 设置C++ 11标准
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# 生成程序名：code_study_for_cpp， 依赖main.cpp文件
add_executable(code_study_for_cpp main.cpp)
