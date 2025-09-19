# Soduku-Solver
Files:
## array_grid_v1 
Takes in the input for sudoku in the form of nxn dimensional array (n should be a square i.e. 4, 9, 16 etc). Solves using a simpler approach looking at sub grid level information. Won't be able to perform well in case when a definite cell level identification is not possible and gives up after a number of iterations provided

## array_grid_v2 backtracking
Takes in the input for sudoku in the form of a nxn dimensional array (n should be a square i.e. 4, 9, 16 etc). Solves using backtracking + sequential placement of values in cells. It is a brute force based and an inorganic approach of solving Sudoku. Can also help give multiple possible solutions

## process_image
Uses open CV to read an image and tries to generate a sudoku grid which can later be solved using backtracking (current implementation)

## array_grid_v1.1
Combination of v1 solver and if not solvable, tries a brute force approach to solve it. Will still five only one solution

## Next steps
To try a combination of the v1 and v2 of array grids, which could basically be solving the sudoku in a more organic way