# Simon Game - Memory Challenge

An interactive web-based implementation of the classic Simon memory game. This project tests and enhances players' memory and concentration skills through increasingly complex sequences of lights and sounds.

## 🚀 Live Demo
https://sanjana3026.github.io/Simon-Game/

## ✨ Features
- **Progressive Difficulty:** The sequence grows longer and more complex as you level up.
- **Retro Aesthetic:** Styled with a dark "arcade" theme and the 'Press Start 2P' font for a nostalgic feel.
- **Interactive Feedback:** Dynamic CSS animations (`.pressed`, `.game-over`) and synchronized audio cues for every interaction.
- **State Management:** Robust logic to track computer-generated patterns vs. user input patterns.

## 🛠️ Tech Stack
- **HTML5:** Semantic structure for the game board.
- **CSS3:** Custom styling, layout, and button animations.
- **jQuery:** Used for DOM manipulation, event handling (click/keypress), and handling game logic.

## 🕹️ How to Play
1. **Start:** Press any key on your keyboard to begin.
2. **Watch:** The game will flash a button and play a sound.
3. **Repeat:** Click the buttons in the exact same sequence.
4. **Advance:** Each correct sequence adds a new random step. 
5. **Game Over:** If you click the wrong button, the screen will flash red, and you can press any key to restart.

## 🧠 What I Learned
- **Event-Driven Programming:** Handling asynchronous user inputs and keypresses.
- **Game Logic Flow:** Managing arrays for pattern tracking and using `setTimeout` to control game timing.
- **Visual Feedback Loops:** Using jQuery to toggle classes and trigger animations based on game state.

## 📂 Project Structure
- `index.html` - The structural markup.
- `style.css` - Visual styling and animations.
- `game.js` - Core game logic and jQuery interactions.
- `/sounds` - Audio assets for button clicks and game over.

---
Made with ❤️ by Sanjana 
