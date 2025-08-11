# 🎮 Tic Tac Toe - Java Console Game

A simple **two-player Tic Tac Toe** game implemented in Java for the console.
Players take turns to place their mark (`X` or `O`) on a 3x3 board until one player wins or the game ends in a draw.

---

## 📌 Features

* Two-player mode (`X` vs `O`).
* Simple console interface.
* Input validation for invalid moves.
* Detects winning conditions across rows, columns, and diagonals.
* Displays the game board after every move.

---

## 🛠 How It Works

1. The game starts with Player **X**.
2. Players enter the **row** and **column** number (0–2) for their move.
3. If the chosen spot is free, it will be marked with the player’s symbol.
4. The game continues until:

   * A player wins, or
   * The board is full (draw).

---

## 🚀 How to Run

### 1️⃣ Clone the repository:

```bash
git clone https://github.com/Anshika-s1ngh/TicTacToe-java.git
```

### 2️⃣ Navigate to the project folder:

```bash
cd tic-tac-toe-java
```

### 3️⃣ Compile the Java file:

```bash
javac com/TicTacToe.java
```

### 4️⃣ Run the game:

```bash
java com.TicTacToe
```

---

## 📷 Example Gameplay

```
 | | 
 | | 
 | | 
Player X enter : 0 0

X| | 
 | | 
 | | 
Player O enter : 1 1

X| | 
 |O| 
 | | 
```

---

## 📄 Code Structure

* **Main Class:** `TicTacToe`
* **Key Methods:**

  * `printBoard()` → Displays the current board state.
  * `haveWon()` → Checks if the current player has won.
  * `main()` → Game loop handling turns, input, and win/draw logic.



## 💡 Future Improvements

* Add single-player mode with AI.
* Detect and announce draws.
* Improve board display formatting.
* Allow replay without restarting the program.



## 🏷 License

This project is licensed under the **MIT License** – feel free to use and modify.

