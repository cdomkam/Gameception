add_library(frogger 
	FroggerFinalVersionDone.cpp
	FroggerFinalVersionDone.h)
target_include_directories(frogger PUBLIC .)
target_link_libraries(frogger simplewindow yslib)
