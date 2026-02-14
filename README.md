# 🐍 Snake Game

A classic Snake Game built using **HTML, CSS, and JavaScript**.
This project includes real-time movement, score tracking, high score storage using LocalStorage, and a live timer. 🚀

---

🚀 Live Demo
https://akshat-1218.github.io/Snake-Game/

## ✨ Features

- 🎮 Snake movement using arrow keys  
- 🍎 Random food generation  
- 📈 Score increases when food is eaten  
- 🏆 High score stored using LocalStorage  
- ⏱ Real-time game timer  
- 💀 Game Over modal  
- 🔁 Restart functionality  
- 📱 Responsive board layout  

---

## 🛠 Tech Stack

- 🌐 HTML5  
- 🎨 CSS3  
- ⚡ JavaScript (Vanilla JS)  
- 💾 LocalStorage API  

---

## 🧠 Game Logic

- The board grid is generated dynamically using JavaScript.
- The snake moves using a game loop created with `setInterval`.
- Collision detection handles:
  - 🚧 Wall collision
  - 🍏 Food collision
- When food is eaten:
  - 🐍 Snake grows
  - 📊 Score increases
  - 🎲 New food spawns randomly
- 🏆 High score remains saved even after page reload.
- ⏹ Timer stops automatically when the game ends.

---