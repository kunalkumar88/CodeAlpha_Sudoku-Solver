📂 Project Structure
Sudoku-Solver/
│
├── sudoku_solver.cpp
└── README.md
🚀 How to Run
Compile

Using g++:

g++ sudoku_solver.cpp -o sudoku_solver
Execute
./sudoku_solver
🎮 Program Menu
================================
        Sudoku Solver
================================
  1. Enter your own puzzle
  2. Use sample puzzle (demo)
================================
Enter choice:
✍️ Input Format

Enter the Sudoku puzzle row by row.

Use numbers 1–9 for filled cells.
Use 0 for empty cells.

Example:

5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9
📷 Example Output
✅ Puzzle Solved!

  +-------+-------+-------+
  | 5 3 4 | 6 7 8 | 9 1 2 |
  | 6 7 2 | 1 9 5 | 3 4 8 |
  | 1 9 8 | 3 4 2 | 5 6 7 |
  +-------+-------+-------+
  | 8 5 9 | 7 6 1 | 4 2 3 |
  | 4 2 6 | 8 5 3 | 7 9 1 |
  | 7 1 3 | 9 2 4 | 8 5 6 |
  +-------+-------+-------+
  | 9 6 1 | 5 3 7 | 2 8 4 |
  | 2 8 7 | 4 1 9 | 6 3 5 |
  | 3 4 5 | 2 8 6 | 1 7 9 |
  +-------+-------+-------+
🔍 Functions Overview
Function	Purpose
printGrid()	Displays the Sudoku board
isValid()	Checks whether a number can be placed safely
solveSudoku()	Solves the puzzle using backtracking
isInitialGridValid()	Validates the input puzzle
inputGrid()	Takes puzzle input from the user
loadSamplePuzzle()	Loads a predefined Sudoku puzzle
🎯 Learning Objectives

This project helps in understanding:

Recursion
Backtracking Algorithms
2D Arrays in C++
Input Validation
Problem Solving Techniques
🤝 Contributing

Contributions, suggestions, and improvements are welcome.

Fork the repository
Create a new branch
Make your changes
Submit a pull request
📜 License

This project is open-source and available under the MIT License.

⭐ If you found this project useful, consider giving it a star on GitHub! ⭐
