cmake_minimum_required(VERSION 3.10)
project(lab03)

add_subdirectory(formatter_lib)
add_subdirectory(formatter_ex_lib)
add_subdirectory(solver_lib)
add_subdirectory(hello_world_application)
add_subdirectory(solver_application)

install(TARGETS hello_world solver DESTINATION bin)
install(TARGETS formatter formatter_ex solver_lib DESTINATION lib)