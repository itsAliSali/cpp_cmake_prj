CMAKE_MINIMUM_REQUIRED(VERSION 3.1)

SET(PROJECT_NAME test_prj)

PROJECT(${PROJECT_NAME})

SET(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)
SET(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/lib)

# SET(CMAKE_CXX_FLAGS_DEBUG "-O3 -Wall -Wextra")

# Required packages:
# FIND_PACKAGE(Boost 1.64 REQUIRED COMPONENTS chrono date_time filesystem log program_options system)
# FIND_PACKAGE(OpenCV REQUIRED)



SET(LIBS
	mylibs
)

ADD_SUBDIRECTORY(lib)
ADD_SUBDIRECTORY(tools)
