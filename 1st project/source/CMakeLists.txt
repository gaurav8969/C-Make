cmake_minimum_required(VERSION 3.5)
project(HelloApp
    VERSION 0.0.1
    DESCRIPTION "Yet another hello world app"
    LANGUAGES CXX)
add_executable(HelloAppExe main.cpp)
target_compile_features(HelloAppExe PRIVATE cxx_std_20)