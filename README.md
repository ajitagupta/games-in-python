# Games In Python

This repository contains simple Python games to demonstrate basic game development principles. Each game is written using Python (core and pygame) libraries, making them easily accessible for beginner and intermediate programmers.

## 1) Hangman

The classic Hangman game where the player has to guess a word by suggesting letters within a limited number of attempts. Each wrong guess adds a part to the hangman drawing. The game ends when the player either guesses the word correctly or runs out of attempts.

### How to Play:
- Run the Python file, and the game will randomly choose a word.
- The player must guess one letter at a time.
- With each correct guess, the letter is revealed in its position in the word.
- For each incorrect guess, the hangman drawing progresses. The game ends when the word is guessed correctly or the drawing is completed.

## 2) Caesar Cipher
This game demonstrates the Caesar Cipher encryption technique. The player can input a message, and the game will encrypt it by shifting each letter a fixed number of places down or up the alphabet. The player can also choose to decrypt an already encrypted message using the same shift value.

### How to Play:
- Run the Python file, and you'll be prompted to enter a message.
- Choose to either encrypt or decrypt the message.
- Enter a key between 1 and 52 (e.g., a key of 3 will shift 'A' to 'D').
- The game will output the encrypted or decrypted message based on your selection.


## 3) Dodger
This is a Python-based arcade game built using the Pygame library. The goal of the game is for the player to dodge falling objects ("baddies") for as long as possible, accumulating points by surviving. The game increases in difficulty as time progresses, with faster and more frequent baddies appearing.

### Key Features:
- Player Controls: Move the player character left or right using the arrow keys to avoid incoming baddies.
- Baddies: Random-sized and random-speed obstacles ("baddies") fall from the top of the screen.
- Increasing Difficulty: Baddies progressively increase in speed and frequency.
- Scoring: The longer you survive, the higher your score. Try to beat the top score!
- Game Over Screen: When the player is hit by a baddie, the game ends, and the score is displayed.

### How to Play:
- Press any key to start the game.
- Use the left and right arrow keys to move the player.
- Avoid colliding with the falling baddies.
- Survive as long as possible to achieve the highest score.

To play Dodger you will be needing the Python game library pygame. Install pygame using ```pip install pygame```.
