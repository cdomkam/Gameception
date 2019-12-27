add_library(tron 
	Tron.cpp
	Tron.h)
target_include_directories(tron PUBLIC .)
target_link_libraries(tron simplewindow yslib)
