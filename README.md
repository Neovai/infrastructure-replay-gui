# infrastructure-replay-gui 
changes made from https://github.com/OSUrobotics/Simulation-Grasping-GUI 
	
	To run: python3 Control_plane_window.py
	Changes:
		removed video capabilities
		added directory with test data
		edited time display
		made timer run actual trial time
	Reason why update function can't update quick enough:
		update_func(self) takes too long
			this is because updating either color_window, sensor_window, or th_window is too slow
## How to Select File:
1. Click open Folder in the main window
2. Go to infrastructure-repaly-gui/real_kinova_tests/
3. select trial_two_Drawer or trial_one_Drawer (do not go into the folder, just simply select it)
4. Click Open Folder. You should see two additional windows pop up. In order to view the contents of the window you must select one of the FSR radio buttons
