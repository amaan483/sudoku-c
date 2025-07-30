# sudoku-c
This program solves a predefined Sudoku puzzle using backtracking algorithm. The puzzle is hardcoded into the code, and the program finds a valid solution and displays it itno 9 x 9 grid format.
## Features
1. Predefined unsolved sudoku puzzle
2. Solves and displays complete puzzle.

## How to run and compile
### Use GCC :
gcc sudoku.c
./a.exe
# Output
The puzzle is solved :

+-------+-------+-------+
| 3 5 8 | 1 2 4 | 9 7 6 |
| 9 2 7 | 5 6 8 | 3 1 4 |
| 4 1 6 | 3 7 9 | 5 2 8 |
|-------+-------+-------|
| 2 6 4 | 8 9 5 | 7 3 1 |
| 5 7 3 | 2 4 1 | 8 6 9 |
| 1 8 9 | 6 3 7 | 4 5 2 |
|-------+-------+-------|
| 6 9 5 | 4 1 3 | 2 8 7 |
| 8 4 2 | 7 5 6 | 1 9 3 |
| 7 3 1 | 9 8 2 | 6 4 5 |
+-------+-------+-------+
