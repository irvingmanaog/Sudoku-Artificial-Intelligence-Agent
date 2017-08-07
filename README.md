# Sudoku-Artificial-Intelligence-Agent
Question 1 (Naked Twins)
Q: How do we use constraint propagation to solve the naked twins problem?

A: A constraint propagation is the idea of applying the same constraints multiple times until a solution is attained or until the constraints can no longer be applied, There are 2 main steps involve in constraints propagation: Elimination and Only-choice.
These 2 steps are applied in the naked-twins problems. First by selecting two boxes with identical sequence of values and removing (or eliminating) these values from other boxes, then split the value one on each box. The strategy is to identify a pair of boxes belonging to the same set of peers that have the same 2 numbers as possibilities, and eliminate these two numbers from all the boxes that have these two boxes as peers. Using the Sudoku game rules, in a unit (complete rows, columns, and 3x3 squares), if 2 digits can only appear in 2 boxes, then they must appear in those 2 boxes only, meaning, no other digits can appear in those 2 boxes and the 2 digits cannot appear in the other boxes within the unit.


Question 2 (Diagonal Sudoku)
Q: How do we use constraint propagation to solve the diagonal sudoku problem?

A: For diagonal Sudoku problem, the same constraint propagation method is applied as of regular Sudoku, using eliminate and only-choice, but apply these methods to the 2 diagonals, on top of columns, squares and rows. This reduces the search time and space significantly.

