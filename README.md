# E06a-Bullets
Hello!

In this exercise, the assignment was to design a shooter game in which a narwhal (the player) has to shoot and kill all the penguins.  To make this possible, I had to write code so that the player could shoot bullets with a left-mouse click, the penguins would take damage and eventually die, and the player's score would increase.

First, to generate the bullets coming from the player, I used the code given to us.  This code applied damage to the bullets and spawned them/allowed them to shoot towards the penguins.

Next, I wrote a program that allowed the bullets to collide with the penguins.  To do this, I allowed the game to constantly update and check for collisions between the bullet sprites and the penguin sprites.  Also, I deleted the pass function that made the bullets simply pass through the penguins.

After this, I made the penguins take damage and eventually die, which in turn increased the players score.  For every bullet that hit a penguin, the player recieved points, and for every time he or she killed a penguin, the score went up.  In order to accomplish this, I set the collision function equal to damage.  Then, I made the code so that when a penguin's hitpoints hit 0, the sprite was killed.

I attempted to do the extra credit but could not figure either of the tasks out.  I guessed that the game end had something to do with the number of enemies left or the player's score but did not know what to do with that information.

Thanks for checking it out!