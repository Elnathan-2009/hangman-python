🎮 Hangman — Python Console Game

A clean, fully-functional Hangman game implemented in Python.
It features ASCII visuals, a large and diverse word list, repeated-guess protection, and input validation.
Designed for beginners and learners who want to understand the fundamentals of loops, conditionals, and game logic in Python.

✨ Features

Random word generation from a large word bank

ASCII hangman art that updates with each wrong guess

Safe input handling (only letters, no duplicates)

Automatic win/lose detection

Beginner-friendly code structure

Very easy to modify and expand

📦 Requirements

Python 3.8+

No external libraries required.

▶️ How to Play

Run the script from your terminal:

python hangman.py


You will:

Guess one letter at a time

See the hangman update with every mistake

Win when all letters are revealed

Lose if the hangman drawing reaches its final stage

📁 Project Structure
/
│── hangman.py        # Main game file
│── README.md         # Project documentation

🧠 How the Game Works (Technical Overview)

This project demonstrates key Python concepts:

Randomization

A word is selected using:

random.choice(words)

Game State Tracking

The game tracks:

Correct letters

Wrong guesses

Letters already used

The ASCII art stage

ASCII Rendering

A dictionary stores each stage of the hangman, updated dynamically based on mistakes.

Loop-Based Game Engine

A while loop manages user input, win/lose checks, and screen updates.

This makes the code a great study example for anyone learning basic Python logic.
