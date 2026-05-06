# 🎮 Simon Memory Challenge

An interactive web-based tribute to the classic 1970s electronic memory game. Challenge your brain by repeating randomized sequences of lights and sounds that get progressively faster and more complex.

## 🚀 [Play the Live Demo](https://sanjana3026.github.io/Simon-Memory-Game/)

---

## ✨ Key Features
- **Persistent High Scores:** Utilizes `localStorage` to save your best score even after the browser is closed.
- **Dynamic UX:** Retro "Press Start 2P" typography with a responsive Neon-Cyberpunk aesthetic.
- **Multi-Sensory Feedback:** Synchronized HTML5 Audio and CSS3 transitions (`.pressed`, `.game-over`) for an immersive experience.
- **State-Driven Logic:** Robust pattern matching algorithm built with jQuery to track user vs. computer sequences.

## 🛠️ Technical Stack

| Category | Technology |
| :--- | :--- |
| **Frontend** | HTML5, CSS3 (Flexbox, Keyframe Animations) |
| **Logic** | JavaScript (ES6), jQuery |
| **Typography** | Google Fonts (Press Start 2P) |
| **Storage** | Web Storage API (localStorage) |

## 🕹️ How to Play
1. **Start:** Press **Any Key** on your keyboard to begin Level 1.
2. **Memorize:** Watch the pattern carefully as the computer flashes a color and plays a sound.
3. **Repeat:** Click the buttons in the exact order shown.
4. **Advance:** Every successful round adds a new random step to the sequence.
5. **Game Over:** One wrong move triggers a "Red Alert" screen flash. Press any key to try and beat your **High Score**!

## 🧠 Engineering Highlights
- **Array Pattern Matching:** Implemented a real-time comparison check that validates user input against a growing `gamePattern` array.
- **Asynchronous Flow:** Leveraged `setTimeout` to manage the transition between the user's turn and the computer's turn, ensuring a natural game rhythm.
- **CSS Specificity:** Solved gradient-over-color rendering issues using the `!important` flag and `background` shorthand for the Game Over state.

## 📂 Project Structure
```text
├── index.html      # Game structure & CDN links
├── style.css       # Neon UI, Flexbox layout, & animations
├── game.js        # Core game loop & state management
└── sounds/        # Audio library (.mp3 files)
```

---
**Developed with ❤️ by [Sanjana](https://github.com)**
