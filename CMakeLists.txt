
cmake_minimum_required(VERSION 3.2)

project(unmlcpp
	VERSION 0.1
	LANGUAGES CXX
)

include_directories(include)

add_library(unmlcpp
	src/unml.cpp
	src/document.cpp
	src/element.cpp
)


