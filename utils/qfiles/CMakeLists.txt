add_executable(qfiles
	qfiles.c)

target_include_directories(qfiles PRIVATE ../common)
target_link_libraries(qfiles PRIVATE common)

