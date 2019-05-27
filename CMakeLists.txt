cmake_minimum_required(VERSION 3.5.0)
project ( StarterApp )
set (CMAKE_CXX_STANDARD 14)
set (Wall)
set (W1)
set (Wfloat-conversion)

include_directories(${CMAKE_SOURCE_DIR}/src})


file(GLOB SOURCES ${CMAKE_SOURCE_DIR}/src/*.cpp)
file(GLOB HEADERS ${CMAKE_SOURCE_DIR}/src/*.h)

add_executable(${PROJECT_NAME} ${SOURCES} ${HEADERS} )


