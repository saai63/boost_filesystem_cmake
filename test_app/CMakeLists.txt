cmake_minimum_required(VERSION 3.10)
add_executable(test_app test_app.cpp)
target_link_libraries(test_app PRIVATE boost_filesystem)
