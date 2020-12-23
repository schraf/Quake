add_executable(bspinfo
	bspinfo.c)

target_include_directories(bspinfo PRIVATE ../common)
target_link_libraries(bspinfo PRIVATE common)

