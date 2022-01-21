# PygameForBeginners
A simple 2D python game designed to teach you the pygame module.

#Mathematics of Pygame
Always Remember that in normal mathematics (x,y) = (0,0) it means in the center of the page but in pygame it is the top left corner of the page 

#Move our Object
First we place our object into direction we fire in our case it is 90 straight to the opposite one the we have to move our object ,for that we have to connect it with the our keyboard keys and after that we have to subtract our value to move us backword and add our value to the forward. For up and down we use y-axis and left and right we use x-axis

Yellow spaceship controls
a for left
s for down
w for up
d for right

Red spaceship controls
right arrow key for left
down arrow key for down
up arrow key for up
left arrow key for right

#Controlling our spaceship speed
In main.py search for VEL if the value is bigger then speed of spaceship also increases

#For creating a middle line
We use boarder and create a rectangle below we have border of the reactangle
WIDTH//2 - 5, 0, 10, HEIGHT
now we want that no player can cross this line so we take there axis and subtract ( or add depend upon which side we are taking about) it by VEL and then check wheather it is greater(or less) then 0 for left and up. for right and down we compare width is smaller then boader.x (for right) and yellow.height is smaller than height(for down) 
do this thing for both side and then spaceship not enable to go in opposite corner and not go outside the border.



