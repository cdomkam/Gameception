add_library(centipede 
	centipede.cpp
	centipede.h)
target_include_directories(centipede PUBLIC .)
target_link_libraries(centipede simplewindow yslib)
