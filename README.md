# infrastructure-replay-gui 
changes made from https://github.com/OSUrobotics/Simulation-Grasping-GUI 
	to run: python3 Control_plane_window.py
	
	Changes:
		removed video capabilities
		added directory with test data
		edited time display
		made timer run actual trial time
	Reason why update function can't update quick enough:
		update_func(self) takes too long
			this is because updating either color_window, sensor_window, or th_window is too slow
