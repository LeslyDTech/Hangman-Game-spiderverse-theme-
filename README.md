# 🕷️ Spider-Verse Hangman

A hangman game built in Python with a Spider-Verse theme.
Guess the hidden Spider-Verse character before the hangman is complete.

---

## How It Works

A random Spider-Verse character name is chosen as the answer. The player
guesses one letter at a time — correct guesses reveal the letter in the
word, wrong guesses build the hangman ASCII art one step at a time. The
game ends when the player guesses the word or runs out of attempts.

---

## What I Learned

- How **dictionaries** store and retrieve ASCII art by key
- How **sets** track guessed letters and prevent duplicates
- How to use `range(len())` to loop through a word and update specific positions
- How to validate user input with `.isalpha()` and `len()`
- How to break a program into multiple **functions** that work together
- How `if __name__ == "__main__"` makes a program importable or standalone

---
