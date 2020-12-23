add_executable(qlumpy
	qlumpy.c
	quakegrb.c)

target_include_directories(qlumpy PRIVATE ../common)
target_link_libraries(qlumpy PRIVATE common)