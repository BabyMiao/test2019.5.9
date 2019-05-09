 cmake_minimum_required(VERSION 3.2)
 PROJECT(helloworld)
 AUX_SOURCE_DIRECTORY(src DIR_SRCS)
 add_executable(helloworld helloworld.cpp)