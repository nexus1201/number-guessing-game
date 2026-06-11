# Number Guessing Game 🎯

A simple Python command-line Number Guessing Game where players try to guess a randomly generated number between 1 and 100 within a limited number of attempts.

## Features

* Three difficulty levels:

  * Easy (10 chances)
  * Medium (5 chances)
  * Hard (3 chances)
* Random number generation
* Input validation using `try-except`
* Hints after each incorrect guess
* Replay option after each game

## How to Play

1. Run the program.
2. Select a difficulty level.
3. Enter a number between 1 and 100.
4. Follow the hints:

   * "The number is greater than..."
   * "The number is less than..."
5. Guess the correct number before you run out of attempts.

## Technologies Used

* Python 3
* Random Module
* Exception Handling (`try-except`)

## Installation

Clone the repository:

```bash
git clone https://github.com/nexus1201/number-guessing-game.git
```

Navigate to the project folder:

```bash
cd number-guessing-game
```

Run the game:

```bash
python main.py
```

## Sample Gameplay

```text
Welcome to the Number Guessing Game!

Please select the difficulty level:
1. Easy (10 chances)
2. Medium (5 chances)
3. Hard (3 chances)

Enter your choice (1, 2, or 3): 2

Great! You have selected the Medium difficulty level.

Enter your guess: 50
Incorrect! The number is greater than 50.

Enter your guess: 75
Congratulations! You guessed the correct number.
```

## Future Improvements

* Score tracking
* High score leaderboard
* Multiple game modes
* Graphical user interface (GUI)
* Difficulty customization

## Author

**John Aldrin Anasis**

* GitHub: https://github.com/nexus1201
* Portfolio: https://nexus1201.github.io/
