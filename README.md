# algorithmXTracing
* created - 11th October 2018

A JavaScript implementation of Donald Knuth's Algorithm X that traces the process of solving Sudoku puzzles. This can alternatively be used to find the exact cover to any incidence/sparce relationship matrix and trace the complex backtracking steps taken in an easily understandable, formatted way.

<br>

### What is algorithm X?
Algorithm X is a general purpose backtracking algorithm devised by Donald Knuth in his paper on Dancing Links - a method for efficiently implementing backtracking algorithms - as a tool to describe his dancing links method. Algorithm X solves NP decision problems; nondeterministic desicion problems solveable in polynomial time.
https://arxiv.org/pdf/cs/0011047

<br>

### How to use (Use with a Sudoku puzzle)

#### 1.
Example unsolved Sudoku (0 represents an empty cell):

| 0 | 3 | 0 | 0 |
| ------------- | ------------- |  ------------- |  ------------- |
| 0 | 0 | 1 | 0 |
| 2 | 0 | 0 | 0 |
| 0 | 0 | 4 | 0 |

          |
          v

`sudoku = [[0, 3, 0, 0], [0, 0, 1, 0], [2, 0, 0, 0], [0, 0, 4, 0]];`

Convert your Sudoku to a two dimensional array as described above. Replace line 22 of the html file with your array. 

<br>

#### 2.
Replace both X's on line 24 shown below with the number of "boxes" (alternatively, `number of sudoku columns / 2`)

`solve(sudoku,[X,X]);` -> `solve(sudoku,[2,2]);`

<br>


#### 3.
Save your html file and double click it to run

