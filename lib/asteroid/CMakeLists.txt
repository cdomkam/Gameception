add_library(asteroid 
	Asteroids.cpp
	Asteroids.h)
target_include_directories(asteroid PUBLIC .)
target_link_libraries(asteroid simplewindow yslib)
