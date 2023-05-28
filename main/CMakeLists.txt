add_executable(main main.c)
target_link_libraries(main print_message)
include_directories(main PUBLIC ../libraries/include)