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
