cmake_minimum_required(VERSION 3.5 FATAL_ERROR)


set(CMAKE_CXX_FLAGS)

set(UNITTESTING_VERSIO_MAJOR 1)
set(UNITTESTING_VERSIO_MINOR 0)
set(LEARN_CMAKE_VERSION_PATCH 0)

set(CMAKE_BUILD_TYPE Debug)
#set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14")


project(TravisTest)

# install()

SET(TARGET_SRC ./main.cpp)
# install
	
add_executable(TravisTest ${TARGET_SRC})

# 