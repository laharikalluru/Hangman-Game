# 🎮 Hangman Game in C++

This is a simple terminal-based **Hangman game** built in **C++** using Object-Oriented Programming concepts. The player attempts to guess a hidden word by suggesting letters within a limited number of attempts.

## ✨ Features

- Random word selection from a predefined list
- Clear display of the Hangman stages
- Tracks correct and incorrect guesses
- Shows guessed letters and remaining attempts
- Fully OOP-based design using inheritance and encapsulation

## 🧠 OOP Concepts Used

- **Abstraction**: Abstract `Game` class with pure virtual functions
- **Encapsulation**: Private/protected members with public interfaces
- **Inheritance**: `HangmanGame` inherits from the base `Game` class
- **Polymorphism**: Overrides virtual functions in derived class

## 📂 File Structure

📁 Hangman-Game/
├── main.cpp # Main game code
└── README.md # Project documentation


## 🔧 How to Compile and Run

### 🛠 Requirements

- C++ Compiler (g++, clang++, or any C++17 compatible compiler)

### 💻 Steps

1. **Clone the repository** (or download ZIP):
   ```bash
   git clone https://github.com/your-username/Hangman-Game.git
   cd Hangman-Game

   
2. Compile the code:
   
   g++ -std=c++17 -o hangman main.cpp

4. Run the game:

   ./hangman


🎯 How to Play
You will be shown the number of letters in the word.

Enter one letter at a time to guess the word.

You have 6 chances to make wrong guesses.

The hangman figure is drawn step-by-step as you make mistakes.

The game ends when you guess the word or run out of attempts.



📃 Sample Words Included

encapsulation

inheritance

polymorphism

abstraction

stand

run

walk

computer

✨ You can modify the word list in main.cpp to add your own words!
   
