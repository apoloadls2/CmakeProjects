cmake_minimum_required(VERSION 3.5)
project(TMath
	VERSION 0.0.1
	DESCRIPTION "Trying to learn something new"
	LANGUAGES CXX)

add_executable(TMAthBinary main.cpp gcem.hpp)
target_compiler_features(TMAthBinary PRIVATE cxx_std_11)