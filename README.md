# ♠️ Blackjack v2

![Status](https://img.shields.io/badge/status-live-success)
![Tech](https://img.shields.io/badge/tech-HTML%20%7C%20CSS%20%7C%20JS-blue)

> **Version 2.0:** A streamlined implementation of the classic casino card game.

## ⚡ Updates in v2
* **State Management:** Robust `isAlive` and `hasBlackJack` logic.
* **Message Feed:** Dynamic game commentary based on card values.
* **RNG Logic:** Improved random card generation (1-11).

## 🎮 How to Play
1.  **Start Game:** Draw your initial hand (2 cards).
2.  **Logic Check:**
    * Sum < 21: "Do you want to draw a new card?"
    * Sum = 21: "You've got Blackjack!"
    * Sum > 21: "You're out of the game!"
3.  **New Card:** Draw one card at a time to get closer to 21.

## 📂 Structure
* `index.html` - The game board.
* `index.css` - Casino styling.
* `index.js` - Game logic and DOM manipulation.
