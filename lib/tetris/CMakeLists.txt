add_library(tetris 
	Tetris.cpp
	Tetris.hpp)
target_include_directories(tetris PUBLIC .)
target_link_libraries(tetris simplewindow yslib)
