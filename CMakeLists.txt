cmake_minimum_required(VERSION 3.16)
project(KatManager)

set(CMAKE_CXX_STANDARD 11)

add_executable(KatManager test.cpp src/Manager.h src/Win32Manager.h)