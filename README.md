# Sudoku-Solver-Backtracking
a recursive BackTracking algorithm for Sudoku
In our Sudoku class, we create a solution method to implement this algorithm. In our implementation, we will stop the algorithm after one solution is found. It is good because a correct Sudoku grid has an uniq solution.

We iterate on the grid, and then, we try to assign a value on an empty cell. If the grid is correct after this assignment, we call recursively the solve method and we return true. Otherwise, we return false and then, the algorithm can try another assignment for the current cell.

At the end of the class, you should have noted the presence of the display method which is used to display a grid on the screen in console mode.



![Excution of the code](https://i.redd.it/jk0kfe2jlc451.png)
