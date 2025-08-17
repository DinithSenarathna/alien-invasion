---

# 👾 Alien Invasion Game

A modern twist on the classic **Alien Invasion arcade game**, built with **Python** and **Pygame**.
Fly your ship, dodge aliens, shoot missiles, and survive as long as you can while the difficulty ramps up!


## 🎮 Features

✅ **Smooth Controls** – Move your ship left/right and fire missiles with ease

✅ **Dynamic Difficulty** – Aliens get faster as you progress

✅ **Scrolling Background** – Parallax-style space background animation

✅ **Sound Effects & Music** – Realistic shooting, explosions & background music

✅ **Scoreboard** – Track your score & compete with friends

✅ **Play Button & Menu** – Easy navigation and restart options

✅ **Leaderboard** – Save & display top scores

---

## 🛠️ Tech Stack

* **Python 3.9+**
* **Pygame** (game loop, rendering, sounds, collisions)
* **OOP** structure for ships, aliens, bullets, and game logic

---

## 📸 Screenshots

### 🛠 Main Menu

![Main Menu](Assets/demo/menu.png)

### 🚀 Gameplay

![Gameplay](Assets/demo/gameplay.png)

### 📊 Scoreboard

![Scoreboard](Assets/demo/scoreboard.png)

---
## ⚡ Installation & Run

1. **Clone the repository**

```bash
git clone https://github.com/DinithSenarathna/alien-invasion.git
cd alien-invasion
```

2. **Create a virtual environment (optional but recommended)**

```bash
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the game**

```bash
python alien_invasion.py
```

---

## 🎮 Controls

| Key   | Action           |
| ----- | ---------------- |
| ⬅️    | Move Left        |
| ➡️    | Move Right       |
| SPACE | Fire Missile     |
| ESC   | Quit Game        |
| Q     | Exit Immediately |

---

## 🏆 Leaderboard

* High scores are saved and displayed on the leaderboard.
* Challenge your friends to beat your score!

---

## 📂 Project Structure

```
Alien-Invasion/
│── alien_invasion.py      # Main game loop
│── Ship.py                # Player ship class
│── Alien.py               # Alien logic
│── Bullet.py              # Bullet mechanics
│── Settings.py            # Game settings
│── GameStats.py           # Game state & lives
│── Scoreboard.py          # Display scores
│── Menu.py                # Main menu UI
│── Assets/                # Images, sounds, backgrounds
│── README.md              # Project documentation
```

---

## 🙌 Credits

* Inspired by the classic **Alien Invasion** game
* Built using **Python + Pygame**
* Assets (images/sounds) from free/open-source repositories

---

## 📌 TODO (Future Improvements)

* 🔥 Power-ups (shields, double-shoot, speed boost)
* 👾 Boss battles
* 🌍 Online leaderboard integration
* 🎨 Custom ship/alien skins

---
