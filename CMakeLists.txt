
cmake_minimum_required(VERSION 3.8)

project(Gameception)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)


add_subdirectory(main)
add_subdirectory(lib/asteroid)
add_subdirectory(lib/centipede)
add_subdirectory(lib/frogger)
add_subdirectory(lib/galaga)
add_subdirectory(lib/pacman)
add_subdirectory(lib/tetris)
add_subdirectory(lib/tron)
add_subdirectory(lib/yslib)
add_subdirectory(lib/simplewindow)
