add_executable(qbsp
	brush.c
	csg4.c
	map.c
	merge.c
	nodraw.c
	outside.c
	portals.c
	qbsp.c
	region.c
	solidbsp.c
	surfaces.c
	tjunc.c
	writebsp.c)

target_include_directories(qbsp PRIVATE ../common)
target_link_libraries(qbsp PRIVATE common)