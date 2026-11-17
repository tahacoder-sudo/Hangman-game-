# Hangman Game in Python

This is a simple command-line Hangman game developed in Python. The project randomly selects a word from a predefined list and allows the player to guess one letter at a time. The player has a limited number of attempts to guess the complete word before the game ends.

I created this project to practice Python fundamentals such as functions, loops, conditional statements, sets, and user input handling while building something interactive and enjoyable.

## Features

- Random word selection
- Letter-by-letter guessing system
- Input validation for incorrect entries
- Detection of repeated guesses
- Limited number of attempts
- Win and lose conditions

## Technologies Used

- Python 3
- Python `random` module

## Project Structure

```bash
Hangman/
│
├── hangman.py
└── README.md
```

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/hangman-game.git
```

2. Move into the project folder:

```bash
cd hangman-game
```

3. Run the program:

```bash
python hangman.py
```

## Example Gameplay

```text
Welcome to Hangman!

_ _ _ _ _ _

Guess a letter: p
Correct guess!

p _ _ _ _ _

Guess a letter: x
Incorrect. You have 5 incorrect guesses left.
```

## What I Learned

While working on this project, I practiced:

- Breaking a program into smaller functions
- Managing user input and validation
- Using sets for efficient storage of guessed letters
- Implementing game logic with loops and conditions

## Future Improvements

Some features that can be added in the future:

- Hangman visual drawing
- Multiple difficulty levels
- Larger word database
- Score tracking system
- Option to replay the game
- Enhanced user experience and gameplay interface

## License

This project is open for learning and personal use.
