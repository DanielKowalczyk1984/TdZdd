CMAKE_MINIMUM_REQUIRED(VERSION 3.11)
project(TdZdd)

add_library(tdzdd INTERFACE)
target_include_directories(tdzdd INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include)