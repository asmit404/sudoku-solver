# Sudoku Solver

## Introduction

This project is a web-based Sudoku solver. It allows users to input a Sudoku puzzle, solve it, and clear the board. The solver uses a recursive backtracking algorithm to find the solution.

## Usage

To use the Sudoku solver, open the `index.html` file in a web browser. The Sudoku board will be displayed, and you can input the puzzle by clicking on the cells and entering the numbers. Once you have entered the puzzle, click the "Solve!" button to solve it. The solver will display the solution on the board.

## Files

- **index.html**: The main HTML file that contains the structure of the Sudoku board and the interface for user interaction.
- **sudoku.js**: The JavaScript file that contains the logic for solving the Sudoku puzzle.

## Interacting with the Sudoku Solver

- **Input Puzzle**: Click on any cell in the Sudoku board and enter a number (1-9).
- **Solve Puzzle**: Click the "Solve!" button to solve the puzzle.
- **Clear Board**: Click the "Clear board" button to clear the entire board.

## Algorithm

The solver uses a recursive backtracking algorithm to find the solution to the Sudoku puzzle. The algorithm works as follows:

1. Find an empty cell in the puzzle.
2. Try all numbers from 1 to 9 in the empty cell.
3. If a number is valid in the cell (i.e., it does not violate the Sudoku rules), move to the next empty cell and repeat steps 2 and 3.
4. If no number is valid in the cell, backtrack to the previous cell and try the next number.

The algorithm continues this process until all cells are filled with valid numbers, resulting in a complete solution to the puzzle.

## License

This project is licensed under the MIT License.
