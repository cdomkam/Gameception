add_library(pacman 
	pacman.cpp
	pacman.h)
target_include_directories(pacman PUBLIC .)
target_link_libraries(pacman simplewindow yslib)
