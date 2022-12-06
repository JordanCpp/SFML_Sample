cmake_minimum_required(VERSION 3.8)

include_directories("dependencies/SFML-2.5.1/include")
link_directories("dependencies/SFML-2.5.1/lib")

add_executable(main "main.cpp")
target_link_libraries(main sfml-window sfml-graphics sfml-main sfml-system)   