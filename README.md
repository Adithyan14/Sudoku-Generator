Sudoku Generator
This Java project generates Sudoku puzzles of a specified size and difficulty. It creates a fully solved Sudoku board and then removes a specified number of digits to create a playable puzzle.

Features
Generates Sudoku puzzles for any N x N grid where N is a perfect square (e.g., 4, 9, 16).
Allows customization of difficulty by specifying the number of missing digits (K).
Ensures valid Sudoku rules are followed for row, column, and subgrid uniqueness.
Provides a simple and efficient algorithm to fill the Sudoku board and remove digits.
Usage
Clone the repository and open the project in your favorite Java IDE.
Run the Generator class to generate and print a Sudoku puzzle.
Example

int N = 9, K = 20;
Generator sudoku = new Generator(N, K);

sudoku.fillValues();
sudoku.printSudoku();
In this example, a 9x9 Sudoku puzzle with 20 missing digits will be generated and printed to the console.
