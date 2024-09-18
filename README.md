# Java-Project-Hangman
Hangman Game
A simple Hangman game implemented in Java. This project allows users to guess a hidden word by entering one letter at a time. The player has a limited number of incorrect guesses before the game ends.

Features
Randomly selects a word from a predefined list.
Displays the word with underscores representing unguessed letters.
Allows players to input guesses and tracks the number of attempts left.
The game ends when the player either guesses the word correctly or runs out of attempts.
How to Play
Run the program.
The game will randomly select a word from the predefined list.
The player will be prompted to guess letters, one at a time.
For each incorrect guess, the number of attempts left will decrease.
The game ends when the word is guessed correctly or the player runs out of attempts.
Rules
You will be given a limited number of attempts to guess the word.
For each incorrect guess, you lose one attempt.
You win by guessing all the letters in the word before running out of attempts.
How to Run
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/hangman-game.git
Navigate to the project directory:
bash
Copy code
cd hangman-game
Compile the Java file:
bash
Copy code
javac HangmanGame.java
Run the program:
bash
Copy code
java HangmanGame
Word List
The game uses a small list of fruit names. The current word list includes:

apple
banana
cherry
date
elderberry
fig
grape
Feel free to extend the word list by modifying the WORDS array in the code.

Future Enhancements
Add more categories of words.
Implement a graphical interface (GUI).
Store the highest scores of players.
Add difficulty levels.
