cmake_minimum_required(VERSION 3.20)
project(test)
add_subdirectory(./Catch2)

add_executable(main_test main.cpp)
target_link_libraries(main_test PRIVATE Catch2::Catch2WithMain)