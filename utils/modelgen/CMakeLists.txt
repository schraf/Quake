add_executable(modelgen
	modelgen.c)

target_include_directories(modelgen PRIVATE ../common)
target_link_libraries(modelgen PRIVATE common)