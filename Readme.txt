----------------------------------------------------------------------------------------
 TACO_GTA_SA  (GTA_SA + sa:mp)
----------------------------------------------------------------------------------------
	Program allows user to move in-game camera and teleport.
	Players location and camera location x,y,z are displayed.

	This type of functions are useful for visual development,
	server script development.
	And maybe for Admin work in server (inside visual range for camera movement)

	Program can be started anywhere and it will detect GTAsa/sa:mp presence.
   
   	Functionality is based on memory read / write.

----------------------------------------------------------------------------------------
 Controls:
----------------------------------------------------------------------------------------

	Hotkey:
		SHIFT+F Disconnect camera from players position (enables free to move camera)
		SHIFT+R Restore camera to players position (Turns spectator mode OFF)
		SHIFT+W Move to North (North direction on Map)	
		SHIFT+S Move to South
		SHIFT+A Move to West	
		SHIFT+D Move to East
		SHIFT+E Move Up
		SHIFT+Q Move Down
		SHIFT+G Teleport to camera location
		SHIFT+Z Turn automatic spectator mode ON/OFF (Usable after SHIFT+F is pressed)
		SHIFT+X (Press once or HOLD): Move Camera one step/many steps.
				
			***Spectator mode is controlled by mouse movement, 
			aimed to the desired direction.
   
		When Player is in vehicle, all camera functions work with vehicle camera.
  		!! Its only usable in short distance from camera, 
    		if vehicle moves far away from camera, some visual distortion appear.
      		

		Left-Right / Up-Down speed is controlled by STEP SIZE.
			
		Hotkey for step size: 
			SHIFT+ (+) = Increase STEP SIZE
			SHIFT+ (-) = Decrease STEP SIZE

		***User can set 'Step change' to select the amount of change made by SHIFT+(+)/SHIFT+(-) 
			
		Teleport save/load Hotkey:
				
			Save: ALT+1,ALT+2,ALT+3,ALT+4,ALT+5,ALT+6,ALT+7,ALT+8,ALT+9
				
			Load: CTRL+1,CTRL+2,CTRL+3,CTRL+4,CTRL+5,CTRL+6,CTRL+7,CTRL+8,CTRL+9
				
			Data is saved to file: Taco_GTA_SA_XYZ.ini / Taco_GTA_SAMP_XYZ.ini

		Teleport function has 5 seconds delay. 
  
----------------------------------------------------------------------------------------
 TACO_GTA_SA_Settings.ini:
----------------------------------------------------------------------------------------

	[Application]
		WindowStateMinimize=1	Use it to start Taco_GTA_SA minimized
		STEP=			step size 
		STEP_INC=		step size change increment
		Form_X=			program window X-position on desktop.
		Form_Y=			program window Y-position on desktop.
		

----------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------
 v 1.0 (30.12.2020)
 
----------------------------------------------------------------------------------------
 v 1.1.4.1 (12.05.2024)
 First public release.
 
----------------------------------------------------------------------------------------
 v 1.1.7.x (21.07.2025)
+ In-vehicle Camera functions (for simgle player)

----------------------------------------------------------------------------------------







----------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------
Code and idea: LARK_1

----------------------------------------------------------------------------------------
Program created with: Embarcadero RAD Studio XE4

----------------------------------------------------------------------------------------




