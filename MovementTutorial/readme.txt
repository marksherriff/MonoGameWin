Sprite movement in video games is usually a pretty simple aspect. We must load an image, and then get its coordinates to move as the game
updates. In Monogame, an understanding on how the game loop cycle works is crucial. First you must create the object you want to be associated with
your sprite. This can be a simple Texture2D but usually you'd rather make a seperate class called Sprite since for the most part, these sprites will have
to carry out and store a complex amount of information. 

The sequence for monogame is loadcontent, and then draw, and then the update cycle is where the game actually runs. Therefore we must load the image, draw it and then
using monogame's keyboard checker we see if the user presses any keys. After this, it is a matter of just updating the coordinates appropriately for the sprite. Ta da! You have
a moving image!

Good job game dev!