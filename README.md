# Java Console Slot Machine 

A lightweight, interactive, and modular console-based Slot Machine game developed in Java. This project was built to reinforce fundamental Object-Oriented Programming (OOP) concepts, control flow structures, and clean code practices.

##  Key Features

* **Dynamic Betting System:** Implements validation logic to handle insufficient funds, negative wagers, and continuous balance tracking.
* **Algorithmic Payout Logic:** Evaluates symbol combinations utilizing clean conditional algorithms to determine double or triple matches.
* **Modern Java Syntax:** Leverages up-to-date Java features including enhanced `switch expressions` for streamlined reward mapping.
* **Modular Architecture:** Decouples core game mechanics into dedicated, reusable methods (`spinRow`, `printRow`, `getPayout`) ensuring high readability and maintainability.

---

## Core Concepts Demonstrated

* **Data Structures:** Arrays for symbol sets and matrix row handling.
* **Randomization:** Built-in `java.util.Random` for simulating unpredictable reel spins.
* **Input Validation:** Safe user input processing using `java.util.Scanner` to prevent invalid states.
* **Flow Control:** Structured `while` loops and nested conditions managing the runtime lifecycle.

---

## Gameplay Mechanics

1. **Initial Bankroll:** Every session initializes with a starting balance of `$100`.
2. **Placing Wagers:** The player inputs a bet amount before each spin.
3. **The Spin:** The system randomly selects 3 symbols from the pool: 🍒, 🍉, 🍋, 🔔, ⭐.
4. **Win/Loss Evaluation:** 
   * **3-of-a-kind:** Highest multiplier payouts (e.g., Triple Stars ⭐ return 20x the bet).
   * **2-of-a-kind:** Moderate multiplier payouts based on adjacent matches.
5. **Session Continuity:** The game prompts the user to continue (`Y/N`) or auto-terminates if the balance hits `$0`.
