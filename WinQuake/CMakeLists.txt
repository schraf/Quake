
add_executable(winquake WIN32
	cd_win.c
	chase.c
	cl_demo.c
	cl_input.c
	cl_main.c
	cl_parse.c
	cl_tent.c
	cmd.c
	common.c
	conproc.c
	console.c
	crc.c
	cvar.c
	gl_draw.c
	gl_mesh.c
	gl_model.c
	gl_refrag.c
	gl_rlight.c
	gl_rmain.c
	gl_rmisc.c
	gl_rsurf.c
	gl_screen.c
	gl_test.c
	gl_vidnt.c
	gl_warp.c
	host.c
	host_cmd.c
	in_win.c
	keys.c
	mathlib.c
	menu.c
	net_dgrm.c
	net_loop.c
	net_main.c
	net_vcr.c
	net_win.c
	net_wins.c
	net_wipx.c
	pr_cmds.c
	pr_edict.c
	pr_exec.c
	r_part.c
	sbar.c
	snd_dma.c
	snd_mem.c
	snd_mix.c
	snd_win.c
	sv_main.c
	sv_move.c
	sv_phys.c
	sv_user.c
	sys_win.c
	view.c
	wad.c
	world.c
	zone.c)

# target_include_directories(client PRIVATE .)
target_compile_definitions(winquake PRIVATE GLQUAKE)
target_link_libraries(winquake PRIVATE opengl32 Winmm dxguid Ws2_32 Comctl32)