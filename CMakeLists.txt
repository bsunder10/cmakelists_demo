cmake_minimum_required(VERSION 3.10)
project(cmake_test)

# Libraries
add_library(print_msg SHARED libraries/print_msg.c)
include_directories(print_msg PUBLIC libraries/include)         # This include for the header file in Library "print_msg.c"

# Main File
add_executable(main main.c)
target_link_libraries(main print_msg)
target_include_directories(main PUBLIC libraries/include)