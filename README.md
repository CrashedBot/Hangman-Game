# **Hangman Game**
This is a simple implementation of the Hangman game in Python. The game randomly chooses a word from a list of words and prompts the player to guess letters in the word until the player either correctly guesses the word or the "hangman" figure is completed.

# How to Play
1- Clone or download the repository to your local machine. 

2- Open a terminal or command prompt and navigate to the directory where the main.py file is located.

3- Run the main.py file in a Python environment by entering the following command: python main.py

4- The game will choose a random word from a list and display the word as a series of dashes, representing the letters in the word.

5- Guess one letter at a time by typing it into the command prompt and pressing Enter.

    If the letter is in the word, it will be revealed in the correct position(s) in the word.
    If the letter is not in the word, a body part of the "hangman" figure will be added to the display.
    If the letter is already guessed, it will state so.

6- Keep guessing letters until you correctly guess the word or the "hangman" figure is completed.

# Configuration Options
The game currently does not have any configuration options that can be modified.

# Contributing
Pull requests are welcome! If you have an idea for a feature or improvement, feel free to submit a pull request with your changes.

# Acknowledgments
This implementation was based on the classic Hangman game and built as a learning exercise in Python programming. The hangman_word.py and hangman_art.py modules were provided as part of the implementation.
