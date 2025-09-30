# 🎮 Tic Tac Toe AI

A Python implementation of **Tic Tac Toe** with an unbeatable AI opponent powered by the **Minimax Algorithm**.
The game logic is fully implemented, and you can integrate it with a Pygame interface or run it directly from the command line.

---

## 📌 Features

* Classic **3x3 Tic Tac Toe** board.
* Supports **two players** or **player vs AI**.
* AI uses **Minimax Algorithm** to always play optimally.
* Detects winners, draws, and invalid moves.
* Easy to extend with **Pygame GUI** for an interactive version.

---

## 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/King-luiz/tictactoe-ai.git
   ```
2. Navigate to the project directory:

   ```bash
   cd tictactoe-ai
   ```
3. (Optional) Install **Pygame** if you plan to use the GUI version:

   ```bash
   pip install pygame
   ```

---

## ▶️ Usage

Run the backend logic (for testing moves and AI decisions):

```bash
python tictactoe.py
```

Run the game with the Pygame interface (if you’ve connected it to `runner.py`):

```bash
python runner.py
```

---

## 📂 Project Structure

```
tictactoe-ai/
│── tictactoe.py   # Core game logic with Minimax AI
│── runner.py      # Pygame interface (optional GUI runner)
│── README.md      # Project documentation
```

---

## 🧠 How the AI Works

* The AI uses the **Minimax Algorithm** to evaluate every possible move.
* `X` tries to maximize the score (+1), while `O` tries to minimize it (-1).
* The AI ensures that it will **never lose**.

---

## 📝 Example

```python
from tictactoe import initial_state, minimax, result, actions

board = initial_state()
print("Available actions:", actions(board))
best_move = minimax(board)
print("AI chooses:", best_move)
```

---

## 📧 Contact

Created by **Lewins Mureithi Nderitu**
📩 Email: [mureithilewins@gmail.com](mailto:mureithilewins@gmail.com)
📱 Phone: **+254 112876340**
🔗 GitHub: [King-luiz](https://github.com/King-luiz)
