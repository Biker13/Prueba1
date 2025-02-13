# Prueba1


## flappy bird

an object that move up and down, to move up you press a single key, it moves down with a gravity, and some pipes that move constantly to the left at diferent heights if the first object touches the ground, the ceiling or the other object dies. So it has a collider to hceck if it touches another object, this is very crucial to any game that has "enemies"

## snake 
constant 2d movement that cahnges diection x,-x,y,-y every time you imput a direction in a confined space, if it touches the walls o himself it dies. another collider but this time it is more calculates because it is by tiles. so you can check the collision only by the position of the head only in relation with the rest of the objects. also a fruit that appears in random locations inside of the borders that the snake isn't in them. 

## asteroids 
2 d movement as well but in this case the movement is defined by a direction and an axis. with the left and right arrows you change the directionn of the spaceship and with the up and down you move forward or backward, you can shoot also. So if you collide(use of colliders) with a meteor you die. 

We can see that in each of them the imputs even being the same, they do differents things, and also you can adjust it to do it constantly as in the asteroids or one time as in the flappy birdor the snake. there is three stages the initial stage that prints in the screen the first frame and the initial position of the objects, the  update game that prints the next frame and change a variable if you make an input and the unload game, that ends the game. appart of that we have a drawgame function to actually put textures in the screen. appart from that we can se that all that functions are used in a main function that runs the project. 
