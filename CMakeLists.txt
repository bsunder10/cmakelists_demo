cmake_minimum_required(VERSION 3.10)
project(cmake_test)

add_library(print_msg SHARED libraries/print_msg.c)


add_executable(main main.c)
target_link_libraries(main print_msg)