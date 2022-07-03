# Greed-game

Greed is a game about collecting gems. The player (#) can move left or right along the bottom of the screen.
Gems (*) and rocks (o) randomly appear and fall from the top of the screen.
If the player touches a gem they earn a point. If they touch a rock they lose a point.
The game continues until the player closes the window.

requirements: You need Python3 and Raylib 

file order: (-) = folder  (+) = file

-greed game

    -game
    
	-casting
	     + actor.py
	     + gems.py
	     + cast.py
	-director
	     + director.py
	-services
	     + keyboard_services.py
	     + video_services
	-shared
	     + color.py
	     + point.py
	+ main.py
