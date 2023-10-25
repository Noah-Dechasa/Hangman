# Hangman Game
This repository contains a simple text-based Hangman game implemented in Python. The objective of the game is to guess the word before running out of attempts.

# Version: 1.0
# Date: October 24, 2023

# How to Play
Run the Python script in your terminal or preferred IDE.
The game will randomly select a word from a predefined list of words.
You will be prompted to guess a letter in the word.
For each incorrect guess, a part of a stick figure gets drawn. You have 7 incorrect guesses before the game ends.
Guess all the letters in the word before running out of attempts to win the game!

# Features
A variety of words to guess from, categorized into different fields like programming, technology, marketing, and more.
Visual representation of the Hangman as you progress through incorrect guesses.
Keeps track of your previous guesses to avoid repetition.
Display of the current state of the word, with correct guesses filled in.

# Code Structure
HANGMANPICS: A list containing strings that represent the hangman figure at different stages of the game.
words: A list of words to be randomly chosen for the game.
chosen_word: The word selected for the current game.
display: A list representing the current state of the word, with underscores representing unguessed letters.
tries: The number of tries the player has left before the game ends.
previous_guesses: A list to keep track of the letters the player has already guessed.
The main game loop iterates through the player's guesses, updating the display and tries count accordingly, until the player either guesses the word or runs out of tries.

# Future Enhancements
Extend the word list or allow players to add their own words.
Implement a difficulty level that adjusts the number of tries the player has.
Incorporate a graphical user interface (GUI) to enhance the player's experience.
