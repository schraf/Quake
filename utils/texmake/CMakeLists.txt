add_executable(texmake
	texmake.c)

target_include_directories(texmake PRIVATE ../common)
target_link_libraries(texmake PRIVATE common)