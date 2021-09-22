cmake_minimum_required (VERSION 3.8)

set(SOURCE_FILES 
	"TaskManager.cpp")

set(HEADER_FILES
	"TaskManager.h")

add_executable (TaskManager ${SOURCE_FILES} ${HEADER_FILES})
