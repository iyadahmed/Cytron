cmake_minimum_required(VERSION 3.16)
project(Cytron)

add_subdirectory(c_utils)
add_executable(cytron_parser cytron_parser.c)
target_link_libraries(cytron_parser PRIVATE c_utils)
