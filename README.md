# 🎭 El Rayo — Luchador Runner

> *A browser-based endless runner game built entirely with HTML, CSS, and JavaScript — no game engines, no libraries, no images, and absolutely LOTS of taco crumbs.

---

## 🕹️ What Is This Game?

Think of the little dinosaur game that pops up when your internet goes out... now instead of the little dinosaur, it's a **Mexican wrestler in a flashy costume**, and instead of cacti, you're dodging **mummies, vampires, werewolves, wizards, and Frankenstein**... who are also wrestlers!!! 🧟‍♂️🧙‍♂️🐺

You press the **SPACE** bar to jump over enemies. The longer you survive, the faster everything moves. Collect power-ups, smash rivals, and chase a high score!

Fair warning: it starts easy. Then it doesn't. 😅

---

## ✨ Features

- 🏃 **Endless runner gameplay** — jumps, obstacles, speed ramp
- 👾 **6 unique rival luchador characters** — each hand-drawn in pixel-style art
- 🌮 **Power-up system** — collect tacos, belts, and chili peppers to charge special moves
- 👊 **3 special attacks** — the Lucha Fist, the Super Burrito rocket, and a Fireball
- ✨ **Invincibility mode** — grab the Golden Chile and smash through everyone for bonus points
- 🎨 **Rich animated background** — a full taqueria bar scene with:
  - 💡 Flickering Edison bulbs
  - 🪅 A swinging piñata rooster on real pendulum physics
  - 🌶️ Scrolling papel picado banners
  - 🕐 A working wall clock (shows your actual time — great for realizing you've been playing for two hours)
  - 🍾 Scrolling bottles in a mirrored bar shelf
  - 🌵 Talavera tiles, ceiling fans, and more
- 📱 **Fully responsive** — scales to any screen size

---

## 🎮 How To Play

| Action | Control |
|---|---|
| Jump | `Space` bar or tap the screen |
| Fire power-up | `Enter` key |
| Start / Retry | Click the button or press `Space` |

### 🏆 Power-Up Guide

| Item | What It Does |
|---|---|
| 🌮 Taco | Collect 3 to charge a **SUPER BURRITO** rocket |
| 🏆 Championship Belt | Charges the **LUCHA FIST** — a giant golden punch |
| 🌶️ Red Chili Pepper | Charges a **FIREBALL** |
| ✨ Golden Chile | **10 SECONDS OF INVINCIBILITY** — smash rivals for +150 pts each! |

---

## 🧠 What I Learned Building This

This project was a deep dive into **web development**. There are no shortcuts or game engines. Everything was built from scratch using three core tools:

### 🏗️ HTML — *The Skeleton*
HTML sets up the structure: the canvas (the drawing board), the score display, and the buttons. Think of it like the blueprints for a building.

### 🎨 CSS — *The Costume*
CSS controls how everything looks: colors, fonts, and layout. The glowing gold championship titles? The aesthetic background? That's CSS styling.

### 🧠 JavaScript — *The Brain*
This is where the game actually *comes to life*. Key concepts used:
- **Variables** — tracking score, speed, player position
- **Functions** — reusable actions like "draw the vampire" or "check for a collision"
- **Loops** — drawing every floor tile, every banner, every particle
- **Math** — `Math.sin()` for smooth bobbing animations; real pendulum physics for the piñata
- **Game loops** — using `requestAnimationFrame` to redraw the screen 60 times per second

### 🖼️ The Canvas API — *The Paintbrush*
This is the best part: **every single element in this game is made of rectangles.** No photos. No sprite sheets. No image files of any kind. The wrestlers, the neon sign, the rooster, the wall clock are all thousands of tiny colored boxes, carefully stacked and positioned. Learning to "think in rectangles" is a surprisingly powerful skill. 🟥🟨

---

## 📁 Project Structure

```
el-rayo/
└── index.html ➡️ The entire game lives here (~1,400 lines)
```

That's it. One file. No build process, no dependencies, no install steps. No folder called `node_modules` that weighs more than a heavyweight champion. 👑

---

## 🚀 How To Run It

1. Download `index.html`
2. Open it in any modern web browser
3. Press **LUCHAR** and jump! 🦘

Or play it directly at: `https://oscaram007.github.io/elrayo4.0/`

---

## 📚 About This Project

This game was built as a **personal learning project** to explore what's possible with just the tools that come built into every web browser. It started as a curiosity and grew into a complete, polished game. Somewhere in the middle there was a phase where the luchador just looked like a sad red and yellow brick (but we don't talk about that). 🟥🟨🧱

As a librarian, I spend my days helping people find information and navigate complex systems. Learning to code felt like a natural extension of that curiosity. There needs to be an understanding of *how* digital tools are built, not just how to use them. This project represents dozens of hours of reading documentation 📖, debugging 🐛, and iterating until things worked. Mostly debugging and stress eating (lol...jk). So many tacos. 😔

---

## 🛠️ Built With

- Pure **HTML5**
- Pure **CSS3**
- Pure **JavaScript** (ES6+)
- The browser's built-in **Canvas 2D API**
- Zero external libraries 💪

---

## 📜 License

MIT — free to use, learn from, and remix. If you build something cool with it, I'd love to see it! 🎉

---

*Made with curiosity, patience, and way too many rectangles. 🟥🟨🟩*
