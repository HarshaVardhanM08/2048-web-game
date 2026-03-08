# 🧩 2048 Web Game

![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![License](https://img.shields.io/badge/license-MIT-green)

A fully playable **2048 puzzle game in the browser** built using **HTML, CSS, and Vanilla JavaScript**.

This project recreates the classic **2048 sliding puzzle game** with smooth animations, keyboard and touch controls, score tracking, and persistent best score storage using **localStorage**.

The entire game — including **HTML structure, CSS styling, and JavaScript logic** — is implemented inside a **single file (`index.html`)**.

---

# 🌐 Live Demo

🔗 **Play the Game**

https://HarshaVardhanM08.github.io/2048-web-game/

---

# 📌 Project Overview

The **2048 Web Game** is a browser-based version of the famous puzzle game originally created by **Gabriele Cirulli**.

Players slide numbered tiles across a **4×4 grid**, merging identical tiles to create larger numbers. The goal is to reach the **2048 tile** while achieving the highest score possible.

This implementation focuses on:

- Clean **Vanilla JavaScript game logic**
- Smooth **CSS animations**
- **Responsive UI design**
- **Keyboard and mobile swipe controls**
- **Persistent best score using LocalStorage**

No external frameworks or libraries are used.

---

# 🎮 Gameplay

### Objective

Merge tiles until you create the **2048 tile**.

### Game Rules

1. The game starts with **two tiles** on a 4×4 board.
2. Each move slides tiles in a chosen direction.
3. Tiles with the **same value merge together**.
4. The merged tile doubles its value.
5. A **new tile (2 or 4)** appears after every move.
6. The player earns points based on merged tile values.
7. The player wins when reaching **2048**, but can continue playing for higher scores.

---

# 🕹 Controls

## Keyboard Controls

| Key | Action |
|----|------|
| ↑ Arrow | Move Up |
| ↓ Arrow | Move Down |
| ← Arrow | Move Left |
| → Arrow | Move Right |
| W A S D | Alternative controls |
| R | Restart the game |

---

## Mobile Controls

| Gesture | Action |
|------|------|
| Swipe Up | Move Up |
| Swipe Down | Move Down |
| Swipe Left | Move Left |
| Swipe Right | Move Right |

The game automatically detects swipe gestures for mobile devices.

---

# ✨ Features

## 🎯 Core Gameplay

- Classic **2048 tile merging mechanics**
- Dynamic tile generation
- Score calculation
- Win detection at **2048 tile**
- Game over detection

---

## 🎨 Modern User Interface

- Clean minimal layout
- Smooth tile animations
- Value-based tile colors
- Responsive board layout

---

## 📊 Score System

- Real-time score updates
- Best score stored using **localStorage**
- Best score persists between browser sessions

---

## 📱 Mobile Friendly

- Swipe gesture support
- Responsive design
- Adaptive tile scaling

---

## 🎉 Game States

- **Win overlay** when reaching 2048
- **Game Over overlay**
- Restart and continue options

---

# 🧠 Game Logic Explained

## 1️⃣ Grid Initialization

The board is represented using a **4×4 matrix**.

Example:

```
[0, 2, 0, 2]
[4, 0, 0, 0]
[0, 0, 2, 0]
[0, 0, 0, 0]
```

Zero represents an empty cell.

---

## 2️⃣ Tile Movement

When a player makes a move:

1. All tiles slide in the chosen direction
2. Identical tiles merge together
3. Score increases based on merged tile value

Example:

Before moving left:

```
[2, 0, 2, 4]
```

After moving:

```
[4, 4, 0, 0]
```

---

## 3️⃣ Tile Generation

After every valid move, a new tile appears.

Probability:

- **90% chance → 2**
- **10% chance → 4**

---

## 4️⃣ Win Condition

The player wins when a tile reaches:

```
2048
```

The player can choose to **continue playing** after winning.

---

## 5️⃣ Game Over Condition

The game ends when:

- The grid is full
- No adjacent tiles can merge

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|--------|
| HTML5 | Structure |
| CSS3 | Styling and animations |
| JavaScript | Game logic and interactivity |
| LocalStorage | Best score persistence |

No frameworks or libraries were used.

---

# 📂 Project Structure

```
2048-web-game
│
├── index.html
├── README.md
└── LICENSE
```

### File Description

**index.html**

The complete game implementation is contained inside this file.

It includes:

- HTML structure
- CSS styling
- JavaScript game engine
- UI rendering
- Event handling
- Animations

**README.md**

Project documentation describing the game, features, and usage instructions.

**LICENSE**

MIT License describing usage permissions.

---

# 🚀 How To Run Locally

### 1️⃣ Clone the repository

```
git clone https://github.com/HarshaVardhanM08/2048-web-game.git
```

### 2️⃣ Navigate to the project folder

```
cd 2048-web-game
```

### 3️⃣ Open the game

Simply open:

```
index.html
```

in any modern web browser.

No server setup required.

---

# 🌍 Deployment (GitHub Pages)

This project is deployed using **GitHub Pages**.

Steps used:

1. Open **Repository Settings**
2. Navigate to **Pages**
3. Select branch **main**
4. Select folder **root /**
5. Save

Your deployed website:

```
https://HarshaVardhanM08.github.io/2048-web-game/
```

---

# 🎨 UI Highlights

- Animated tile appearance
- Tile merge animations
- Value-based tile colors
- Minimalistic interface
- Responsive board layout

---

# 📈 Future Improvements

Possible upgrades for the project:

- 🔊 Sound effects
- 🌙 Dark / Light theme toggle
- 🧠 AI autoplay mode
- 🏆 Online leaderboard
- 🎯 Larger board sizes (5×5 or 6×6)
- 💾 Save and resume game state
- 🎮 Multiplayer competitive mode

---

# 📚 Skills Demonstrated

This project demonstrates important **frontend development skills**:

- DOM manipulation
- Algorithmic game logic
- Event handling
- Mobile gesture detection
- Responsive web design
- LocalStorage usage
- CSS animation techniques

This makes the project **portfolio-ready and suitable for showcasing frontend expertise**.

---

# 🤝 Contributing

Contributions are welcome.

Steps:

1. Fork the repository
2. Create a feature branch

```
git checkout -b feature-name
```

3. Commit changes

```
git commit -m "Add feature"
```

4. Push branch

```
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

If you like this project, please give it a **star ⭐ on GitHub**.
