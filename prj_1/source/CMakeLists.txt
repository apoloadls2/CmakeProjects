cmake_minimum_required(VERSION 3.5)
project(HelloApp 
        VERSION 0.0.1
        DESCRIPTION "Trying to learn something new"
        LANGUAGES CXX)  
        
add_executable(AppBinary main.cpp)
target_compile_features(AppBinary PRIVATE cxx_std_11)