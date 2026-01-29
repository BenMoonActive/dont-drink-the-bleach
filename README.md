# 🍼 Don't Drink the Bleach! (אל תשתה ת'אקונומיקה!)

> **A frantic 3D survival game where you must stop thirsty toddlers from drinking the forbidden cleaning juice.**

### 🎮 [PLAY THE GAME HERE](https://[YOUR_USERNAME].github.io/[REPO_NAME])

*(Click the link above to play in your browser)*

---

## 📖 About the Game
"Don't Drink the Bleach!" is a fast-paced browser arcade game built with **Three.js**. The objective is simple but stressful: You are the responsible adult in a room full of toddlers who are inexplicably attracted to a bottle of bleach on the table.

As time goes on, more kids appear from the doors and windows. How long can you keep them safe?

## 🕹️ How to Play
* **Objective:** Prevent any kid from touching the bleach bottle on the table.
* **Controls:**
    * **PC:** Click on a kid to push them away.
    * **Mobile:** Tap on a kid to push them away.
* **Game Over:** The game ends immediately if a kid reaches the bottle. Your score is your survival time.

## ✨ Features
* **3D Graphics:** Built using the [Three.js](https://threejs.org/) library.
* **Physics-based Gameplay:** Kids have velocity and react to "push" forces with inertia and friction.
* **Progressive Difficulty:**
    * **0s:** One kid.
    * **30s:** A second kid enters through the **door**.
    * **60s:** A third kid enters through the **window**.
* **Responsive Design:** Works on both Desktop and Mobile (supports touch events).
* **Procedural Audio:** Sound effects generated in real-time using the Web Audio API (no external sound files required).
* **Hebrew Interface:** Fully localized UI.

## 🛠️ Technical Details
* **Engine:** Three.js (r128)
* **Language:** HTML5, CSS3, Vanilla JavaScript
* **Lighting:** Directional Light with Shadow Mapping + Ambient Light
* **Camera:** Orthographic projection for an isometric "dollhouse" look.

## 🚀 Installation / Running Locally
Since this is a single-file game, you don't need to install anything!

1.  Clone this repository or download the `index.html` file.
2.  Open the file in any modern web browser (Chrome, Safari, Firefox).
3.  **Note:** For the best experience on mobile, ensure the file is hosted (like on GitHub Pages) rather than opening a local file path.

## 📝 License
This project is open source. Feel free to modify and share!
