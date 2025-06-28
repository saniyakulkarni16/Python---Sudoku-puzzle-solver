🧩 Sudoku Solver using Python

This project is a simple **Sudoku puzzle solver** built in Python using **backtracking** — a powerful algorithmic technique for solving constraint satisfaction problems like Sudoku.

💡 How It Works:

* The Sudoku board is hardcoded as a 2D list within the Python script.
  
* The solver uses recursion and backtracking to fill the empty cells (`0` or `.`) with valid digits (1–9).
  
* At each step, the algorithm checks if a number placement is valid by ensuring:

* It's not already in the current row
    
* It's not already in the current column

* It's not already in the current 3×3 box

* If a number fits, it moves forward. If it hits a dead end, it backtracks by resetting the cell and trying the next number.

Input:

The initial Sudoku board is defined within the code like this:

board = [
    [5, 3, 0, 0, 7, 0, 0, 0, 0],
    [6, 0, 0, 1, 9, 5, 0, 0, 0],
    [0, 9, 8, 0, 0, 0, 0, 6, 0],
    ...
]

Output:

After running the script, the terminal prints both the **initial Sudoku board** and the **solved board**, as shown in the screenshot.

