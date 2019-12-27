add_library(yslib 
	ysglfontdata.c
	ysglmaketextbitmap.c
	yspng.cpp
	ysglmaketextbitmap.h
	yspng.h
	ysglfontdata.h)
target_include_directories(yslib PUBLIC .)
