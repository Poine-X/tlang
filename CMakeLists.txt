cmake_minimum_required(VERSION 3.10)
project(Tlang CXX)

include_directories(./include)
aux_source_directory(./src SRC_DIR)


add_executable(tlang ${SRC_DIR})