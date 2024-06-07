# PROJECT_Sudoku_Solver
### Sudoku Solver

This Java project implements a Sudoku solver using a backtracking algorithm to find the solution for a given Sudoku puzzle. 

#### How it works
- The solver takes a 9x9 Sudoku grid as input, where 0 represents empty cells to be filled in.
- It iterates through each cell, attempting to place numbers 1 to 9 in empty cells, ensuring that each placement adheres to Sudoku rules: no repeated numbers in rows, columns, or 3x3 subgrids.
- If a number placement violates Sudoku rules, it backtracks and tries a different number until a valid solution is found.

#### Usage
1. Define the Sudoku puzzle by filling in the grid with numbers, using 0 for empty cells.
2. Run the `main` method of the `SudokuSolver` class.
3. The program will output the solved Sudoku grid if a solution exists.
            
