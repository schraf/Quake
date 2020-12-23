add_executable(light
	entities.c
	light.c
	ltface.c
	threads.c
	trace.c)

target_include_directories(light PRIVATE ../common)
target_link_libraries(light PRIVATE common)

