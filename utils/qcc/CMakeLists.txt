add_executable(qcc
	pr_comp.c
	pr_lex.c
	qcc.c)

target_include_directories(qcc PRIVATE ../common)
target_link_libraries(qcc PRIVATE common)