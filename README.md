# Hangman Game

## Introduction
Welcome to Hangman, a classic word-guessing game that challenges your vocabulary and guessing skills. In this game, you'll attempt to guess a secret word letter by letter before running out of attempts. Each incorrect guess brings you one step closer to hanging the poor stick figure!

## How to Play
- Run the Hangman game on your terminal or preferred environment.
- The program will choose a random word from a predefined list of words. The length of the word will be displayed as underscores, representing each letter's position.
- Guess a letter: Enter a letter (a-z) and press "Enter".
- The game will inform you if the letter is correct and reveal its positions in the word or inform you if the letter is incorrect.
- If your guess is incorrect, a part of the hangman's figure will be drawn.
- Keep guessing letters until you correctly identify the entire word or run out of attempts (hang the poor stick figure).
 ```Note: You can customize the list of words by modifying the word_list in the code to add or remove words.```

## Rules
- The secret word will be randomly selected from the list of words.
- You have a limited number of attempts to guess the word. The number of attempts may vary, but typically it's around 6 to 8.
- You cannot guess the same letter twice. Repeated letters won't count against your attempts.
- If you correctly guess all the letters in the word before running out of attempts, you win the game.
- If you run out of attempts before guessing the word, you lose the game, and the stick figure is hung.
