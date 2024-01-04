# Java Sudoku Solver
This Java application is designed to solve Sudoku puzzles using a backtracking algorithm.

## How it Works
The program uses a backtracking algorithm to fill in the missing cells of a Sudoku board. It follows these steps:

## Input: The Sudoku puzzle is represented as a 9x9 grid in the code.
Solving: The solver checks for empty cells (marked as 0) and attempts to place numbers from 1 to 9 while ensuring the placement is valid according to Sudoku rules.
Backtracking: If a number doesn't fit or violates Sudoku rules, the algorithm backtracks and tries a different number, continuing until the puzzle is solved or determined unsolvable.
## Usage
The Main.java file contains the solver implementation. You can input your Sudoku puzzle in the code by modifying the board array with your unsolved puzzle.

Run the Main class to see the solver in action. Upon successful completion, it will display the solved puzzle.

## Example Puzzle:
java
Copy code
int[][] board = {
    {7, 0, 2, 0, 5, 0, 6, 0, 0},
    {0, 0, 0, 0, 0, 3, 0, 0, 0},
    {1, 0, 0, 0, 0, 9, 5, 0, 0},
    {8, 0, 0, 0, 0, 0, 0, 9, 0},
    {0, 4, 3, 0, 0, 0, 7, 5, 0},
    {0, 9, 0, 0, 0, 0, 0, 0, 8},
    {0, 0, 9, 7, 0, 0, 0, 0, 5},
    {0, 0, 0, 2, 0, 0, 0, 0, 0},
    {0, 0, 7, 0, 4, 0, 2, 0, 3}
};
## Contributions
Contributions are welcome! Feel free to fork this repository, make improvements, and create pull requests.
