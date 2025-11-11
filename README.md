# Turtle Game 🐢

A simple browser-based **Turtle Graphics simulator** built with HTML, CSS, and JavaScript.  
Control a turtle using buttons or arrow keys to draw on a grid — similar to Logo turtle graphics.

---

## 🎮 Features
- Move the turtle up, down, left, or right
- Toggle pen up/down to draw lines
- Reset the floor grid
- Smooth animation and keyboard shortcuts

---

## 🕹️ Controls
| Action | Key/Button |
|---------|-------------|
| Move Up | ↑ or "Move Up" |
| Move Down | ↓ or "Move Down" |
| Move Left | ← or "Move Left" |
| Move Right | → or "Move Right" |
| Toggle Pen | Space |
| Reset Floor | R |

---

## 🧠 How It Works
- The grid is dynamically generated in JavaScript (`turtle.js`).
- The turtle’s position and pen state are tracked using simple DOM updates.
- The `.marked` class fills cells when the pen is down.
