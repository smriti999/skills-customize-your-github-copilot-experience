
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build the classic word‑guessing game using Python strings, loops, and user input. This exercise reinforces fundamental programming concepts and gives you practice structuring a simple interactive program.

## 📝 Tasks

### 🛠️ Hangman Core Functionality

#### Description
Implement the main game loop, allowing the program to randomly choose a word, accept letter guesses from the player, and update the display accordingly.

#### Requirements
Completed program should:

- Randomly select words from a predefined list
- Accept letter guesses and display current progress in an `_ _ _` format
- Track the number of incorrect guesses remaining
- End the game when the word is guessed or attempts are exhausted
- Display appropriate win or lose messages

### 🛠️ Input Validation and Enhancements

#### Description
Add checks to ensure the player inputs a single letter and handle repeated guesses gracefully. Optionally, you can add simple features like showing previously guessed letters.

#### Requirements
Completed program should:

- Reject invalid input (e.g. more than one character or non‑letters)
- Inform the player if a letter has already been guessed
- (Optional) Display a list of past guesses or a rudimentary ASCII hangman graphic
