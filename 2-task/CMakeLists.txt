cmake_minimum_required(VERSION 3.0.0)
project(puter VERSION 0.1.0)

set(MY_INCLUDE_DIR ${CMAKE_SOURCE_DIR}/include)
set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})

add_subdirectory(src)