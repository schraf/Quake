add_executable(vis
	flow.c
	soundpvs.c
	vis.c)

target_include_directories(vis PRIVATE ../common)
target_link_libraries(vis PRIVATE common)