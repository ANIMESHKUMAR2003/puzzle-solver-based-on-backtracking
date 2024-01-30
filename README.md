# Puzzle-Solver for ADSA project


This repo contains both an interactive pentomino puzzle and a built-in solver. The solver uses backtracking to explore all possible board configurations until it encounters a solution. You'll have to download Pygame if you want to play with the interactive solver, but otherwise vanilla Python is all you need.
group members:-

Animesh kumar

Abdul qadir

Himanshu kumar

Gui.py is the main running file other files are just supporting files for the code

Some popular applications of this algorithm are finding solutions for Sudoku, brute-forcing passwords, and path-finding in mazes.

Meanwhile, recursion is defined as:

the process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called as recursive function.

Hence, we will be implementing a backtracking algorithm using recursion to search for a solution that will lead us to the desired state.

I find that the most tedious part of implementing this algorithm is representing the puzzle and the operations in code. However, once that is done, writing the general algorithm that does the actual solving is not that difficult at all.

Implement recursive backtracking once and it should be easy tore-use the pattern to solve similar puzzles.

Project Prerequisite
This project requires good python knowledge and a pygame library that we will use for this project. For this project, we use an algorithm to reverse the sudoku solution which is a backtracking algorithm.

</br>
</br>

<p align="center">
  <img src="images/solutions.gif" width="300" height="300"/>
</p>

# File Structure
gui.py -> interactive pentomino puzzle

tangram.py -> main body of the actual solver, cleanest implementation

tangram_multi.py -> inherits from tangram.py, uses Python's multiprocessing library to speed up the simulation

remove_duplicates.py -> checks a list of solved boards for duplicates

setup.py -> parameters for gui.py

solutions -> contains a pickle file with all 16,146 unique solutions to the puzzle
