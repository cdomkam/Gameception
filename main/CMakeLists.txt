

add_executable(Gameception MACOSX_BUNDLE flythrough.cpp)

target_link_libraries(Gameception asteroid centipede frogger galaga pacman simplewindow tetris tron yslib)

file(COPY ../assets DESTINATION ${CMAKE_BINARY_DIR}/main)
