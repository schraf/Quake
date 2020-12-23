add_executable(sprgen
	sprgen.c)

target_include_directories(sprgen PRIVATE ../common)
target_link_libraries(sprgen PRIVATE common)