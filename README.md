# SudokuSolverUsingBackTracking
This is a Sudoku game solving algorithm using Backtracking.

==> What is Backtracking?
           Backtracking is simply reverting back to previous step or soultion as soon as we determine that out current solution cannot be continued into a complete one. We will use this principle of backtracking to implement the sudoku solver algorithm.
       
==> How it works?  
Algorithm : 

Starting with an incomplete board:
--> Find some empty space
--> Attempt to place the digits 1-9 in that space
--> Check if that digit is valid in the current spot based on the current board
--> a. If the digit is valid, recursively attempt to fill the board using steps 1-3.
    b. If it is not valid, reset the square you just filled and go back to the previous step.
--> Once the board is full by the definition of this algorithm we have found a solution




