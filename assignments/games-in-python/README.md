
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman game in Python using strings, loops, conditionals, and user input. By the end of this assignment, students will create a complete game loop with win and loss conditions.

## 📝 Tasks

### 🛠️ Build the Core Game Setup

#### Description
Create the main setup for the Hangman game, including a predefined list of words, random word selection, and variables needed to track progress.

#### Requirements
Completed program should:

- Use a predefined list of possible words
- Randomly select one word at the start of the game
- Initialize the hidden word display using underscores (for example, `_ _ _ _`)
- Set a starting number of incorrect guesses remaining

### 🛠️ Implement Guessing and Game Outcomes

#### Description
Add player input and game logic so the user can guess letters, see progress updates, and finish with a clear win or loss message.

#### Requirements
Completed program should:

- Accept letter guesses from the player
- Reveal correctly guessed letters in the word display
- Decrease remaining attempts for incorrect guesses
- End the game when the full word is guessed or attempts reach zero
- Display a clear win message or loss message at the end
