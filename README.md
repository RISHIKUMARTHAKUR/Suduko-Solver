# 🔢 Sudoku Solver 

An efficient Sudoku solver built in **C++** using the **Backtracking algorithm**. This project demonstrates classic recursive backtracking techniques to fill a partially completed Sudoku board with valid digits.

---

## 🛠️ Tools & Technologies Used

* **C++**
* **Data Structures & Algorithms (Backtracking)**
* **Visual Studio Code**
* **Git & GitHub**

---

## 📌 Features

* Solves any valid 9x9 Sudoku puzzle
* Implements a clean and modular **backtracking** solution
* Easy to understand and modify
* Command-line interface for quick testing

---

## 🧠 Algorithm Used

> **Backtracking**: A recursive approach that tries all possibilities and backtracks upon encountering invalid states — ensuring valid placement of numbers based on Sudoku rules.

---

## 🧾 Sample Input

```cpp
vector<vector<int>> board = {
    {5, 3, 0, 0, 7, 0, 0, 0, 0},
    {6, 0, 0, 1, 9, 5, 0, 0, 0},
    {0, 9, 8, 0, 0, 0, 0, 6, 0},
    {8, 0, 0, 0, 6, 0, 0, 0, 3},
    {4, 0, 0, 8, 0, 3, 0, 0, 1},
    {7, 0, 0, 0, 2, 0, 0, 0, 6},
    {0, 6, 0, 0, 0, 0, 2, 8, 0},
    {0, 0, 0, 4, 1, 9, 0, 0, 5},
    {0, 0, 0, 0, 8, 0, 0, 7, 9}
};
```

---

## ✅ Output (Solved Sudoku)

```
5 3 4 | 6 7 8 | 9 1 2  
6 7 2 | 1 9 5 | 3 4 8  
1 9 8 | 3 4 2 | 5 6 7  
------+-------+------
8 5 9 | 7 6 1 | 4 2 3  
4 2 6 | 8 5 3 | 7 9 1  
7 1 3 | 9 2 4 | 8 5 6  
------+-------+------
9 6 1 | 5 3 7 | 2 8 4  
2 8 7 | 4 1 9 | 6 3 5  
3 4 5 | 2 8 6 | 1 7 9  
```

---

## 🚀 How to Run

```bash
g++ sudoku_solver.cpp -o sudoku
./sudoku
```

---

## 📂 File Structure

```
📁 SudokuSolver
│
├── sudoku_solver.cpp     # Main C++ implementation
├── README.md             # Project documentation
└── .gitignore            # Build/output exclusion
```
