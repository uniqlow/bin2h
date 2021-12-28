cmake_minimum_required(VERSION 3.7 FATAL_ERROR)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

project("bin2h")

add_executable(bin2h
	bin2h.cpp
)
target_include_directories(bin2h
	PRIVATE
	${CMAKE_CURRENT_BINARY_DIR}
)
