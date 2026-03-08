# 🧩 2048 Web Game

A fully playable **2048 puzzle game in the browser** built using **HTML, CSS, and Vanilla JavaScript**.

This project recreates the classic 2048 sliding tile game with smooth animations, keyboard and touch controls, persistent score tracking, and a responsive UI.

---

# 🌐 Live Demo

🔗 **Play the Game**

https://HarshaVardhanM08.github.io/2048-web-game/

---

# 📌 Project Overview

The **2048 Web Game** is a browser-based implementation of the popular puzzle game originally created by **Gabriele Cirulli**.

Players slide numbered tiles across a **4×4 grid**, merging identical tiles to create larger numbers. The goal is to reach the **2048 tile** while maximizing the score.

This project focuses on:

- Clean **Vanilla JavaScript game logic**
- Smooth **CSS animations**
- **Responsive design**
- **LocalStorage score persistence**
- **Keyboard + mobile swipe support**

No frameworks or libraries are used — everything is built from scratch.

---

# 🎮 Gameplay

### Objective
Combine tiles of the same number until you reach **2048**.

### How It Works

1. The game starts with **two tiles** on a 4×4 board.
2. Tiles slide in the direction of the player's move.
3. When **two identical tiles collide**, they merge into one.
4. The tile value doubles.
5. The player earns points equal to the merged tile value.
6. A **new tile (2 or 4)** appears after every move.
7. The game ends when **no valid moves remain**.

---

# 🕹 Controls

### Keyboard Controls

| Key | Action |
|----|------|
| ↑ Arrow | Move Up |
| ↓ Arrow | Move Down |
| ← Arrow | Move Left |
| → Arrow | Move Right |
| W A S D | Alternative controls |
| R | Restart game |

### Mobile Controls

| Gesture | Action |
|------|------|
| Swipe Up | Move Up |
| Swipe Down | Move Down |
| Swipe Left | Move Left |
| Swipe Right | Move Right |

---

# ✨ Features

### 🎯 Core Gameplay
- Classic **2048 mechanics**
- Tile merging logic
- Dynamic tile generation
- Game over detection
- Win detection when reaching **2048**

### 🎨 Modern UI
- Clean and minimal design
- Smooth tile animations
- Color-coded tiles
- Responsive layout

### 📊 Score System
- Real-time score updates
- **Best score saved using localStorage**
- Persistent across browser sessions

### 📱 Mobile Friendly
- Swipe gesture support
- Responsive layout
- Optimized tile scaling

### 🎉 Game States
- Win overlay when reaching **2048**
- Game Over overlay
- Restart / Keep Playing options

---

# 🧠 Game Logic

The game logic works through the following process:

### 1️⃣ Grid Initialization

A **4×4 matrix** represents the game board.

Example:

```
[0, 2, 0, 2]
[4, 0, 0, 0]
[0, 0, 2, 0]
[0, 0, 0, 0]
```

---

### 2️⃣ Movement Algorithm

When a move is triggered:

1. Remove empty cells  
2. Merge identical neighbors  
3. Update score  
4. Refill remaining spaces with zeros  

Example:

Before move left:

```
[2, 0, 2, 4]
```

After move:

```
[4, 4, 0, 0]
```

---

### 3️⃣ Tile Generation

After each move, a new tile appears:

- **90% chance → 2**
- **10% chance → 4**

---

### 4️⃣ Win Condition

If a tile reaches **2048**, the player wins.

---

### 5️⃣ Game Over Condition

The game ends when:

- The board is full
- No adjacent tiles can merge

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|--------|
| HTML5 | Structure |
| CSS3 | Styling & animations |
| JavaScript | Game logic |
| LocalStorage | Best score persistence |

---

# 📂 Project Structure

```
2048-web-game
│
├── index.html
├── style.css
├── script.js
├── LICENSE
└── README.md
```

### File Description

**index.html**

Main page containing:

- Game board
- Score panel
- Overlays
- Controls

**style.css**

Handles:

- Layout
- Tile colors
- Animations
- Responsive design

**script.js**

Contains:

- Game engine
- Tile merging logic
- Input handling
- Rendering system

---

# 🚀 How To Run Locally

### 1️⃣ Clone Repository

```bash
git clone https://github.com/HarshaVardhanM08/2048-web-game.git
```

### 2️⃣ Navigate into Folder

```bash
cd 2048-web-game
```

### 3️⃣ Open the Game

Simply open:

```
index.html
```

in any browser.

No server required.

---

# 🌍 Deployment (GitHub Pages)

This project is deployed using **GitHub Pages**.

Steps:

1. Go to **Repository Settings**
2. Open **Pages**
3. Select branch **main**
4. Select folder **root /**
5. Save

Your game will be available at:

```
https://HarshaVardhanM08.github.io/2048-web-game/
```

---

# 🎨 UI Highlights

- Animated tile appearance
- Merge animation effects
- Color gradient tiles
- Responsive board layout
- Minimal clean interface

---

# 📈 Possible Future Improvements

Some ideas for extending the project:

- 🔊 Sound effects
- 🌙 Dark / Light theme toggle
- 🧠 AI autoplay mode
- 🏆 Online leaderboard
- 🎯 Custom grid sizes (5×5 / 6×6)
- 💾 Save & resume game state
- 🎮 Multiplayer competitive mode

---

# 📚 Skills Demonstrated

This project demonstrates important **frontend development skills**:

- DOM manipulation
- Game algorithm design
- Event handling
- Responsive UI design
- State management
- LocalStorage usage
- CSS animation techniques

This makes the project **excellent for portfolios and resumes**.

---

# 🤝 Contributing

Contributions are welcome!

If you'd like to contribute:

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Add feature"
```

4. Push branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Harsha Vardhan Maradana**

GitHub  
https://github.com/HarshaVardhanM08

LinkedIn  
https://www.linkedin.com/in/harsha-vardhan-maradana-1a9911330/

---

# ⭐ Support

If you like this project, please **give it a star ⭐ on GitHub**.

It helps the project grow and supports the developer.

---

# 🧩 Merge Tiles • Think Strategically • Reach 2048 🚀
