cmake_minimum_required (VERSION 3.5.1)
project (Test)

include_directories (includes)

file(GLOB SOURCES "src/*.cc")

add_executable (Test ${SOURCES})
