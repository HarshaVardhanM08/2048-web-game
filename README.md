# 🧩 2048 Web Game

🔗 **Live Demo:**  
https://HarshaVardhanM08.github.io/2048-web-game/

> A browser-playable version of the popular 2048 puzzle game — fully built using HTML, CSS, and Vanilla JavaScript.

---

## 📌 Project Overview

This is a fully responsive and interactive **2048 web game** inspired by the classic sliding puzzle. Players merge numbered tiles by swiping or using keyboard arrow keys to reach the tile **2048**.

This web version includes smooth animations, score tracking, mobile support, local storage saving of best scores, and a modern UI — all implemented without any frameworks or external libraries.

Key highlights:

- ✔ Browser playable (no Python or backend)
- ✔ Works on desktop + mobile
- ✔ Keyboard + touch controls
- ✔ Persistent best score via localStorage
- ✔ Visually appealing tile animations
- ✔ Light and dark color mode friendly UI

---

## ✨ Features

### 🧠 Core Gameplay
- Slide tiles using arrow keys or swipes
- Merge same numbered tiles
- Random new tiles spawn after each move
- Game ends when no moves remain
- Win condition when 2048 tile appears

### 🎮 Controls
| Input | Action |
|-------|--------|
| Arrow Keys | Move tiles |
| WASD | Alternative controls |
| Touch Swipe | Mobile sliding |

### 📊 Score System
- Track current score
- Best score stored locally
- Live updating UI score panel

### 📱 Responsive & Interactive
- Adapts to all screen sizes
- Touch interaction support
- Modal overlays for win/game-over
- Smooth tile transition animations

---

## 🛠️ Tech Stack

| Technology | Role |
|------------|------|
| HTML5 | Structure |
| CSS3 | Styling + Animations |
| JavaScript | Game logic + Interactivity |
| localStorage | Persistent best score |

No frameworks. Pure, clean frontend code.

---

## 🧠 Game Logic Explained

1. The game initializes a 4×4 grid.
2. Two tiles start in random positions (2 or 4 value).
3. A move combines tiles of equal value in the direction of the swipe/keypress.
4. Merged tiles increase score.
5. A new tile appears after each successful move.
6. Best score is updated and stored.
7. Game ends when no valid moves remain.

The logic ensures no invalid moves are allowed and handles both keyboard and touch interactions seamlessly.

---

## 📂 Project Structure

```
2048-web-game/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

- `index.html` — Main page
- `style.css` — All styling and layout
- `script.js` — Game logic and interactivity
- `README.md` — This documentation

---

## 🖥️ How to Run Locally

### 1️⃣ Clone the repository

```
git clone https://github.com/HarshaVardhanM08/2048-web-game.git
```

### 2️⃣ Open the project

```
cd 2048-web-game
```

### 3️⃣ Launch the game

Open **index.html** in your browser.

That’s it! 🎉 The game will run instantly in any modern browser.

---

## 🌍 Hosting via GitHub Pages

This project is published as a static website using GitHub Pages:

1. Go to **Repository → Settings**
2. Open **Pages**
3. Select branch: `main`
4. Folder: `/ (root)`
5. Save

Your deployed site lives at:

🟢 https://HarshaVardhanM08.github.io/2048-web-game/

---

## 🎨 UI Highlights

- Tile color gradients based on value
- Animated tile movement
- Clean minimal layout
- Score panel and controls aligned for usability
- Light/dark theme support via CSS variables

---

## 📈 Future Enhancements

Here are some upgrades you can make later:

- 🔊 Add sound effects
- 🎨 Theme selector (dark/light)
- 🧠 AI auto-play option
- 🏆 Leaderboard with Firebase
- 🎯 Different grid sizes (5×5, 6×6)
- 💾 Export/save game state

---

## 📜 Skills This Project Demonstrates

- DOM manipulation
- Algorithmic game logic
- Event handling (keyboard + touch)
- Responsive web design
- localStorage management
- CSS animation & layout design

This makes the project resume-ready and ideal for showcasing frontend expertise.

---

## 🤝 Contributing

Contributions are welcome!

If you’d like to contribute:

1. Fork this repo
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Harsha Vardhan Maradana**

🔗 GitHub:  
https://github.com/HarshaVardhanM08

🔗 LinkedIn:  
https://www.linkedin.com/in/harsha-vardhan-maradana-1a9911330/

---

## ⭐ Support

If you enjoyed this project, don’t forget to ⭐ the repo!

---

# 🧩 Merge, Think, Aim for 2048! 🚀
