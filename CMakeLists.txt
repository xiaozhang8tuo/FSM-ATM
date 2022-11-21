cmake_minimum_required(VERSION 3.1)
project(ATM)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g  -Wall -O0 -pthread")

aux_source_directory(${CMAKE_SOURCE_DIR} MAIN_SOURCES)

add_executable(ATM 
               ${MAIN_SOURCES}                
)
