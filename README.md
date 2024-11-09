Name: K.N Bharath

Introduction:
         This program is designed to solve Sudoku puzzles automatically. Given an input grid representing an unsolved puzzle, the program uses an algorithm to fill in the missing numbers, following standard Sudoku rules. Each row, column, and 3x3 sub-grid in the 9x9 puzzle must contain all numbers from 1 to 9 without repetition.

Features:
        Automated Input Processing: Accepts a 9x9 grid where blank or unknown cells are represented by 0s.
Efficient Algorithm: Utilizes a backtracking algorithm to find the correct values for each blank cell.
Validation: Ensures that the puzzle follows Sudoku rules before solving, detecting if a solution is possible.
User-Friendly Output: Displays the completed puzzle clearly in a 9x9 grid format.


How It Works :
Input: Enter a 9x9 grid, with blank cells represented by 0s. For example:

5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9

Execution: Run the program, and it will attempt to solve the puzzle using the backtracking algorithm. The algorithm tries numbers in blank cells and backtracks when conflicts arise, eventually filling in the entire grid.

Output: The program will print the completed puzzle or notify if the puzzle cannot be solved.

Example
Input Puzzle:

5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9
Solved Output:

5 3 4 6 7 8 9 1 2
6 7 2 1 9 5 3 4 8
1 9 8 3 4 2 5 6 7
8 5 9 7 6 1 4 2 3
4 2 6 8 5 3 7 9 1
7 1 3 9 2 4 8 5 6
9 6 1 5 3 7 2 8 4
2 8 7 4 1 9 6 3 5
3 4 5 2 8 6 1 7 9
