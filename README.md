# ArcWormy
Wormy Game with ArcPy
In order to help guide me in my Python programming project I used the book Making Games with Python & Pygame. It is a programming book that covers the Pygame game library for the Python programming language. Each chapter gives you the complete source code for a new game and teaches the programming concepts from these examples. The book is available under a Creative Commons license and can be downloaded in full for free from http://inventwithpython.com/pygame.   You are free: To Share — to copy, distribute, display, and perform the work.  To Remix — to make derivative works.
The object of the game is for the worm to eat as many apples and get bigger without hitting the edge of the screen which causes the game to be over.
It guided me step by step for the codes to make the game. Steps are as follows:
Set up code: This is the code at the start of the program that sets up some constant variables used in the game and imports the necessary modules. 
Main function: The main function starts the game and then  will return when the player’s worm collides into the edge of the wall or itself and causes game over.
Separate function: This function sets a random start point for the worm and apple each game.
The loop: This is the main game loop using the while statement and the event handling loop which tells the game when to terminate().  
Moving the worm: Moves the worm by adding a segment in the direction it is moving by using the insert() list method which can add items anywhere inside the list.
Collision Detection functions: Checks if the worm has hit itself or the edge and Checks to see if the worm has eaten an apple
Drawing the screen:  Draws the grid, worm, apple, and score to the display.  Also for the text “Press a key to play.”
Start screen:  The function to create the rotating word 'wormy' for the start screen.
Game over screen:  Similar to the start screen without the same graphics.  This function also allows the Game over screen to stay on until any other key is pressed 
Drawing functions: Separate functions to draw the scrore, worm, apple, and grid.  Since the 'for' loop was used, we don’t have to type out all 56 pygame.draw.line() calls.
Main function: After all the functions and constants and global variables have been defined and created, the main() function is called to start the game.
I copied and pasted the code into the GUI inside ArcGIS, python 2.7.13.
Problems I encountered are as follows:
1. Did not work with first run
2. Several unexpected indents to fix
3. Pygame was not in the standary library of  Python 2.7.13
Professor Miller helped me to install pygame using pip install for Python 2.7.13 on the computer. 
I ran the code and it worked!
I pushed my new commit into my git repository.
I modified the worm color from darkgreen and green to red and white.  Changed the apple color from red to green. 
I pushed my modified commit into my git repository.
Although programming is not my strong suit, it was interesting to run a code that worked and produced a video game. 
