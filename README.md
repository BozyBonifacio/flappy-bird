# 🐦 Flappy Bird — HTML5 Canvas Clone

A fully playable Flappy Bird clone built with pure HTML5 Canvas, CSS, and vanilla JavaScript. No frameworks, no dependencies (except the Google Font for the retro look). Works in any modern browser on Windows, Mac, iOS, or Android.

---

## 🎮 How to Play

| Input | Action |
|-------|--------|
| `Click` | Flap |
| `Tap` (mobile) | Flap |
| `Spacebar` or `↑` | Flap |

- Avoid the green pipes and the ground.
- Each pipe you pass scores **+1 point**.
- Your **best score** is saved locally between sessions.

---

## 🚀 Running Locally

No build step or server required — just open the file:

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/flappy-bird.git
cd flappy-bird

# Open in browser (Windows)
start index.html

# Open in browser (Mac/Linux)
open index.html
```

Or simply double-click `index.html` in File Explorer.

---

## 🌐 Play Online (GitHub Pages)

1. Go to your repo → **Settings** → **Pages**
2. Set source to `main` branch, root `/`
3. Your game will be live at:  
   `https://YOUR_USERNAME.github.io/flappy-bird/`

---

## 📁 Project Structure

```
flappy-bird/
└── index.html      ← entire game in one file
└── README.md
```

---

## ✨ Features

- Smooth physics (gravity, flap velocity, rotation)
- Randomly generated pipe gaps every run
- Animated bird — wing flap, body tilt
- Scrolling ground and parallax clouds
- Live score HUD + best score persistence (`localStorage`)
- Game Over screen with "NEW BEST!" detection
- Idle float animation before game starts
- Mobile-friendly (touch events, `user-scalable=no`)

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 Canvas API | Game rendering |
| Vanilla JavaScript | Game logic & physics |
| CSS3 | Layout & styling |
| Google Fonts | Press Start 2P (retro font) |
| localStorage | Best score persistence |

---

## 📝 License

MIT — free to use, modify, and distribute.
