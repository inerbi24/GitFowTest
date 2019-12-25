cmake_minimum_required(VERSION 3.10)

if(TOOLCHAIN STREQUAL mobis)
	message(STATUS "Use mobis toolchain")
elseif(TOOLCHAIN STREQUAL lge)
	message(STATUS "Use lge toolchain")
elseif(TOOLCHAIN STREQUAL vs2017)
	message(STATUS "Use vs2017 toolchain")
endif()

project(Test)

add_subdirectory(HelloWorld)