# Soldier-Tracker

Installation: 

	1. Download the SQF file "QS_icons.sqf".
	
	2. Copy it to your mission file.
	
	3. Configure script to your liking (inside the file).
	
	4. Ensure it is executed by the mission.
	
			In client/player init (initPlayerLocal.sqf)
				
				[] execVM "QS_icons.sqf";
			
			or 
				
				[] execVM "scripts\QS_icons.sqf";    (if in a folder called scripts in your mission directory.)
			
			Follow instructions posted in the below link
				
				http://forums.bistudio.com/showthread.php?184108-Soldier-Tracker-(-Map-and-GPS-Icons-)
	
	5. Run mission!