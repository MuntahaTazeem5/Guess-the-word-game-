# Guess-the-word-game-
Think you can outsmart the alphabet? This Python mini-game picks a secret letter, and it's your job to find it! With limited tries and instant feedback, it's a quick, fun way to sharpen your Python skills. Perfect for beginners exploring input handling, loops, and game logic.


📜 Overview

This is a console-based word guessing game. The program randomly selects a word from a predefined list. The player must guess the word by entering one letter at a time. Correct guesses reveal the letter in its correct position; incorrect guesses reduce the number of available attempts. The game ends when the word is correctly guessed or all attempts are used up.

🎮 Gameplay Example
Current Word: _ _ _ _ 
Guess a letter: t

Current Word: _ _ _ _ 
Guess a letter: i
Wrong guess! Attempts left: 9
Wrong guess! Attempts left: 8
Great guess!
Wrong guess! Attempts left: 7

Current Word: _ _ i _ 
Guess a letter: o
Great guess!
Wrong guess! Attempts left: 6
Wrong guess! Attempts left: 5
Great guess!

Current Word: o _ i o
Guess a letter: h
Wrong guess! Attempts left: 4
Great guess!
Congratulations! You guessed the word: ohio

🧠 Features

✅ Random word selection from a custom word bank

✅ Input handling and case normalization

✅ Limited number of attempts (10)

✅ Visual representation of guessed letters

✅ Encouraging and informative user feedback

🧰 Technologies Used

Language: Python 3

No external libraries required – Runs using built-in Python modules only

📦 How to Run

Clone this repository:

git clone https://github.com/yourusername/python-word-guess-game.git
cd python-word-guess-game


Run the script:

python3 game.py


💡 Make sure Python 3 is installed on your machine.

📚 Word Bank

The current word bank includes:

rizz, ohio, sigma, tiktok, skibidii


Want to add your own words? Modify the word_bank list in game.py.

🐞 Known Issues

❌ Attempts are incorrectly deducted even on correct guesses (see else inside loop).

❌ Game may prematurely end due to logic bugs.

Fix Suggestion: Move the else and attempts decrement logic outside the for loop for accurate behavior.

🚀 Future Improvements

 Fix the attempt counter bug

 Add support for full-word guesses

 Implement GUI using tkinter

 Add a difficulty level selector (easy, medium, hard)

🤝 Contributing

Contributions are welcome! Feel free to fork the repo, make changes, and submit a pull request.

📝 License

This project is licensed under the MIT License. See the LICENSE
 file for more information.

✨ Acknowledgements

Inspired by classic Hangman games and Gen Z internet culture.
