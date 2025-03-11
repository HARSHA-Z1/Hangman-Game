# Hangman Game in C++

## Overview

This is a simple Hangman game implemented in C++. The game randomly selects a word from a predefined list of fruit names, and the player has to guess the word by entering one letter at a time. The game ends when the player either guesses the correct word or runs out of attempts.

## Features

- Random word selection from a list of fruit names
- User input for letter guessing
- Keeps track of guessed letters
- Displays the hangman progressively as incorrect guesses are made
- Maximum of 6 incorrect attempts

## How to Play

1. Run the program.
2. The game will display a blank word with underscores representing letters.
3. Enter one letter at a time to guess the word.
4. If the letter is correct, it will be revealed in the word.
5. If the letter is incorrect, you will lose an attempt, and the hangman drawing will progress.
6. Win by guessing the entire word before running out of attempts.
7. Lose if all 6 attempts are used up before the word is completed.

## Compilation and Execution

### Using g++

```sh
 g++ hangman.cpp -o hangman
 ./hangman
```

## Technologies Used

- C++
- Standard Template Library (STL)

## Future Enhancements

- Expand the word list
- Implement different difficulty levels
- Add graphical representation instead of ASCII art
- Allow multiplayer mode

## Author

Developed as a simple C++ project for fun and learning.

Harsha Vardhan
