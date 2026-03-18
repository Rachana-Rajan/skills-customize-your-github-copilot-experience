
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman word-guessing game in Python using strings, loops, conditionals, and user input.

## 📝 Tasks

### 🛠️ Task 1: Hangman game core logic

#### Description
Implement the game loop that picks a secret word, receives letter guesses from the player, updates display state, and checks win/lose conditions.

#### Requirements
Completed program should:

- Randomly choose a word from a predefined list
- Accept single-letter guesses and validate input
- Show current word progress with placeholders (e.g., `_ a _ _ _`)
- Track and display remaining incorrect guess attempts
- End with a win message when the word is fully guessed
- End with a lose message when attempts reach zero

### 🛠️ Task 2: User experience enhancements

#### Description
Improve player interaction with clear prompts and result output.

#### Requirements
Completed program should:

- Display letters already guessed
- Reject duplicate letter guesses with a friendly message
- Show the full secret word at game end
- Allow restart prompt (optional)

## 💡 Optional extensions

- Add difficulty levels with different attempt limits
- Load words from an external file (e.g., `words.txt`)
- Add ASCII art for Hangman stages

