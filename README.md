# 🎮 Java 2D Coin Collector Game

A 2D game built with **Java Swing** where the player moves around a grid-based board and collects coins to score points.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Swing](https://img.shields.io/badge/Java_Swing-GUI-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

---

## 🕹️ Gameplay

- Move your player around the board using **Arrow Keys**
- Collect **coins** scattered across the grid to earn points
- New coins appear as you collect them — keep your score climbing!

---

## 📸 Project Structure

```
java_2d_game/
├── App.java        # Entry point — creates the game window (JFrame)
├── Board.java      # Game loop, rendering, keyboard input handling
├── Player.java     # Player class — position, movement, sprite
├── Coin.java       # Coin class — random placement, collision detection
└── images/
    ├── player.png
    ├── coin.png
    ├── green-circle.png
    ├── blue-square.png
    ├── black-diamond.png
    └── double-black-diamond.png
```

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java | Core programming language |
| Java Swing (JPanel, JFrame) | GUI and game rendering |
| ActionListener + Timer | Game loop (ticks every 25ms) |
| KeyListener | Keyboard input for player movement |
| ArrayList | Managing multiple coin objects |
| OOP (Classes & Objects) | Player, Coin, Board design |

---

## ▶️ How to Run

### Prerequisites
- Java JDK 8 or above installed
- Any IDE (IntelliJ IDEA, Eclipse, VS Code) or terminal

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/arshad029/java_2d_game.git

# 2. Navigate to project folder
cd java_2d_game

# 3. Compile all Java files
javac *.java

# 4. Run the game
java App
```

---

## 🎯 Key Concepts Implemented

- **Game Loop** — Timer fires every 25ms to update game state and re-render
- **Object-Oriented Design** — Separate classes for Player, Coin, and Board
- **Collision Detection** — Detects when player lands on a coin's tile
- **Random Coin Placement** — Coins spawn at random grid positions using `Random`
- **Keyboard Input** — Real-time movement via `KeyListener`
- **2D Graphics Rendering** — Custom `paintComponent()` draws all game elements

---

## 🚀 Future Improvements

- [ ] Add score display on screen (HUD)
- [ ] Add obstacle tiles to block movement
- [ ] Add a timer / countdown mode
- [ ] Sound effects on coin collection
- [ ] High score tracking (file I/O)
- [ ] WASD key support

---

## 👨‍💻 Author

**Arshad Ali**
- GitHub: [@arshad029](https://github.com/arshad029)
- LinkedIn: [Arshad Ali](https://www.linkedin.com/in/arshad-ali-58a4a7290)

---

