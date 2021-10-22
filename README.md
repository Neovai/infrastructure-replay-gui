# Data visualization for Grasping


	1.Control_plane_window.py: The main file and create the control plane in this file.
	2.Force_graph_window.py: Create the force window and show the force curve in this window.
	3.TD_window.py: Create the 2D window and use color to shown the change of pressure on each sensor.
	4.THD_window.py: Create the 3D window and use pyopenGL to paint drawer and door model.
	5.read_file_csv.py: Read the data from csv file and return three data matrix(Angle/Distance, force data, time)
	6.model_data.py: Store the data(vertexs, edges, face) of drawer and door model. The data was collected from blender
	7.Vedio_window.py: Create the vedio window and use opencv read the vedio file and then connect to the timmer of control window.
	8.blender.txt: Generate the vertex, edges, face data of drawer and door model.
	
	For recently time update, it is mainly to update the video file. Also, fixed some display problems of the control window and 
	fixed the model switch when switching the door data to drawer data. 
	The current animation refresh rate can only be maintained at 3 frames per second.
