Description
This is a simple JavaScript-based dice game that simulates a two-player dice roll and determines the winner. The game uses random numbers to represent the outcomes of two dice rolls and displays the result to the players.

How to Play
Open the HTML file in a web browser.
Two dice images will be displayed on the screen, representing the results of two random dice rolls.
The player with the higher dice roll wins. If the rolls are the same, it's a draw.
Code Explanation
The JavaScript code generates random numbers for two dice rolls, updates the displayed dice images, and declares the winner based on the outcome of the rolls. Here's a breakdown of the key code sections:

Random Number Generation:

randomNumber1 and randomNumber2 are generated to simulate the dice rolls.
The random numbers are between 1 and 6 to represent the six faces of a standard die.
Image Handling:

randomDiceImage and randomDiceImage2 are used to determine which dice image to display based on the random numbers.
randomImageSource and randomImageSource2 construct the image file paths.
Updating the HTML:

The setAttribute method is used to change the source of two <img> elements to display the dice images.
Determining the Winner:

The code checks which player has the higher random number and updates the <h1> element to display the result.
If player 1 wins, it displays "Player 1 Wins!" with a flag emoji.
If player 2 wins, it displays "Player 2 Wins!" with a flag emoji.
If it's a draw, it displays "Draw!"
Usage
You can play this game by opening the HTML file in your web browser. Just refresh the page to play another round.

Contributing
Feel free to contribute to this project by improving the game, adding new features, or fixing any issues.



Enjoy the game! 🎲🎉
