# 🎮 Tetris in C++ using Raylib

A clean and minimal implementation of **Tetris** built using **C++** and the **Raylib** graphics library.  
This project focuses on using a **2D array** as the primary data structure to represent the game grid, while maintaining clear logic for piece movement, collision detection, and row clearing.

---

## 📌 Features

- Smooth Tetris gameplay using Raylib rendering  
- 20x10 grid implemented using a **2D integer array**  
- Detects full rows and shifts blocks down  
- Colored tetromino rendering  
- Efficient logic for movement & boundary checking  
- Highly readable and modular C++ code

---

## 🛠️ Tech Stack

- **C++ (17/20 standard)**
- **Raylib** (installed locally or via Homebrew on macOS)
- **VSCode** (recommended development environment)
- **2D Array Grid System**

---

## 🧩 Data Structure Used

### **Game Grid → 2D Array**
```cpp
int grid[20][10];
