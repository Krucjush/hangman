# hangman

My version of the hangman game.
The game starts, and prints as many underscores `_` as there are letters in the randomly chosen password.
Player can make 5 mistakes before the game is over.
If the player enters a letter entered previously, but this letter is in the password, then the player does not lose a heart.
If the player enters a letter that is not in the password, then the player loses a heart, regardless of whether the letter was already guessed.
The current state of player's heart can be tracked through appearing ASCII art each time a letter is given.
User wins when the word gets all uncovered.
