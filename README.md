## Rock-Paper-Scissors Game 🎮

A simple Python implementation of the classic Rock-Paper-Scissors game, where you play against the computer.

## Features
- Player chooses **rock**, **paper**, or **scissors**.
- Computer randomly selects its choice.
- Game result is displayed with fun descriptive messages.
- Handles ties, wins, and losses.

## How to Run

1. **Clone or download** this project to your local machine.
2. Make sure you have **Python 3** installed.
3. Open a terminal in the project folder and run:
   ```bash
   python rock_paper_scissors.py
Follow the prompt to enter your choice:

css
Copy
Edit
Enter a choice (rock, paper, scissors): rock
See the result printed in the console.

Example Output
css
Copy
Edit
Enter a choice (rock, paper, scissors): paper
you chose paper, computer chose rock
paper covers rock! You win!
Code Overview
get_choices() → Handles user input and randomly generates the computer’s choice.

check_win(player, computer) → Compares choices and returns the game result.

Main section runs the game by:

Getting choices

Checking who wins

Printing the result

Requirements
Python 3.x

No external dependencies.

