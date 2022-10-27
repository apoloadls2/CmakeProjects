cmake_minimum_required(VERSION 3.5)
project(AppTest2
        VERSION 0.0.1
        DESCRIPTION "Just for fun"
        LANGUAGES CXX)

#target
add_executable(AppTestBin main.cpp) #what is to word and from what
target_compile_features(AppTestBin PRIVATE cxx_std_11) #some extras defintions
