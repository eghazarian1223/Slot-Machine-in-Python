# Slot-Machine-in-Python

Welcome to the Python Slot Machine simulation! This is a simple command-line game where you can simulate playing a slot machine.

## How to Play

1. Run the `slot_machine.py` script in your terminal.
2. You will be prompted to deposit an initial amount of money into your balance.
3. Press Enter to play a round of the slot machine. You can press 'q' and Enter to quit the game.
4. For each round, you can choose the number of lines to bet on (between 1 and 3) and the bet amount per line (between $1 and $100).
5. The slot machine will display the results of the spin, including the symbols in each column.
6. If your spin results in winning combinations on the selected lines, your winnings will be displayed along with the winning lines.

## Game Rules

- You start with a balance that you can deposit at the beginning.
- The goal is to maximize your balance by making successful bets on the slot machine.
- The game has a set of symbols (A, B, C, D) each with different frequencies and values.
- You can bet on up to 3 lines and choose the amount to bet per line.
- Winning combinations are checked vertically across columns.
- The game will display your current balance after each round.

## Code Explanation

The `slot_machine.py` script contains the code for simulating the slot machine game. Here's an overview of the main components:

- `deposit()`: Allows you to deposit an initial amount of money to start the game.
- `check_winnings(columns, lines, bet, values)`: Checks if there are any winning combinations in the spin results.
- `get_slot_machine_spin(rows, cols, symbols)`: Generates a random spin result for the slot machine.
- `print_slot_machine(columns)`: Prints the results of the slot machine spin in a user-friendly format.
- `get_number_of_lines()`: Gets the number of lines you want to bet on.
- `get_bet()`: Gets the amount you want to bet per line.
- `spin(balance)`: Simulates a spin of the slot machine and calculates the winnings.
- `main()`: The main game loop that manages the player's balance and gameplay.

## Requirements

- Python 3.x

## How to Run

1. Clone this repository to your local machine.
2. Open a terminal and navigate to the repository's directory.
3. Run the command: `python slot_machine.py`



