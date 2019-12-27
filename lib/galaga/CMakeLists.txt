add_library(galaga 
	galaga.cpp
	galaga.h)
target_include_directories(galaga PUBLIC .)
target_link_libraries(galaga simplewindow yslib)