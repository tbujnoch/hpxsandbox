cmake_minimum_required(VERSION 3.3.2)
project(hpxsandbox CXX)
find_package(HPX REQUIRED)
add_hpx_executable(hpxsandbox
	SOURCES main.cpp
	COMPONENT_DEPENDENCIES iostreams)