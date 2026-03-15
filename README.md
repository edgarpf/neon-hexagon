# Neon Hexagon 🛑✨

[![Play Live](https://img.shields.io/badge/Play-Live-success?style=for-the-badge&logo=github)](https://edgarpf.github.io/neon-hexagon/)

A fast-paced, minimalist arcade survival game inspired by Terry Cavanagh's *Super Hexagon*. Dodge the incoming walls, survive as long as possible, and beat your high score! 

**[🕹️ Play the game here!](https://edgarpf.github.io/neon-hexagon/)**

## 🚀 Features

* **Zero Dependencies:** The entire game logic, styling, and rendering are contained within a single `index.html` file using vanilla JavaScript and the HTML5 `<canvas>` API.
* **Responsive & Mobile-Ready:** Fully fluid layout that adapts to any screen size. Includes built-in touch controls optimized for smartphones.
* **Retro Arcade Aesthetic:** Features a custom CSS-based CRT scanline effect, pulsing animations, and randomly generated neon color palettes (Synthwave, Matrix, Inferno, Ice).
* **Dynamic Difficulty Scaling:** As the timer goes up, the walls close in faster, the world rotates quicker, and the player's movement speed scales to keep the gameplay fair but intensely challenging.
* **Procedural Audio:** Sound effects (like the retro sawtooth wave explosion) are synthesized in real-time using the Web Audio API—no external `.mp3` or `.wav` files required.
* **Custom Particle System:** A physics-based particle explosion triggers upon player collision.

## 🎮 Controls

### Desktop
* **Rotate Left:** `Left Arrow` or `A`
* **Rotate Right:** `Right Arrow` or `D`
* **Start / Restart:** `Space`

### Mobile
* **Rotate Left:** Touch and hold the left half of the screen.
* **Rotate Right:** Touch and hold the right half of the screen.
* **Start / Restart:** Tap anywhere on the screen.

## 🛠️ How to Run Locally

Since the game has no external dependencies or assets (other than a Google Font), you don't need a local server to run it.

1. Clone the repository:
   ```bash
   git clone [https://github.com/edgarpf/neon-hexagon.git](https://github.com/edgarpf/neon-hexagon.git)
2. Open the folder and double-click index.html to open it in any modern web browser.
