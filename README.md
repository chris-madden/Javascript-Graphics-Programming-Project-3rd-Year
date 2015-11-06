#Game Title

Square Invasion

#Game Description

This is a shooting game where squares are falling and trying to take out your spaceship. You must shoot down the squares and stop them from landing below you.

###Game Rules 

You can move your ship left and right only. 

Squares fall from top of screen and will respawn randomly each time one is killed.

Only one square will be on the screen at any one time.

Kill squares by shooting bullets from ship.

If squares hit your ship or reach the ground it's game over

You will get points for each square you shoot.

You can only fire one bullet at a time, another can be fired when first bullet has left screen (so be accurate with your shooting).

###Controls (User Interaction)

######Moving ship

There are two controls schemes for moving your ship, you can use:

1. 'A' and 'D' for moving ship left and right, respectively.
2. Left and Right arrow keys for moving ship left and right, respectively.

######To shoot bullets from your ship

1. Use spacebar

###Collisions

Collisions occur between: 

1. Bullets and squares
2. Bullets and top of screen
3. Squares and ship
    1. The top of ship
    2. The left corner of ship
    3. The right corner of ship
4. Squares and bottom of screen
5. Left side of ship and left side of screen
6. Right side of ship and right side of screen


####Notes:

*There are no collision detected when the square hits the side of your ship 
i.e the angle part of the triangle (top of ship with left corner and top of ship with right corner).
However, this still results in game over as square will now reach bottom of screen without being shot.*

######Bugs

*Bug occurs when game is over and the spacebar is pressed. This will restart the game with the ship invisible but can still be moved and fired*

*Quit button wont work if opened externally E.G opened from live preview in Brackets*

####References

*Mozilla website was used for the random method*
```
getRandomIntInclusive();
```
*Link is below*
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)