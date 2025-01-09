
# Concurrent Set Card Game

## Overview
This Java project implements a multithreaded version of the card game **Set**. The game leverages Java Concurrency mechanisms to handle players, the dealer, and the game logic in a synchronized manner.

---

## Features
- **Player Management**:
  - Supports human and computer players.
  - Simultaneous game actions with multithreading.
- **Game Logic**:
  - Identifies valid sets of cards based on their features.
  - Awards points for correct sets and applies penalties for incorrect ones.
- **Dealer Functionality**:
  - Manages card distribution, shuffling, and game flow.
- **Dynamic Game Configuration**: Supports customizable gameplay parameters.
- **Graphical User Interface**: Prebuilt UI for game visualization.

---

## How to Run
1. Build using Maven: `mvn compile`.
2. Run: `mvn exec:java`.
3. Ensure proper configuration in `config.properties`.

---

## Key Files
- Game logic: `Dealer.java`, `Player.java`, `Table.java`
- Configuration: `config.properties`
- Testing: Unit test files in `src/test`.

---

## Notes
- Ensure efficient and correct synchronization.
- Avoid redundant locking to maintain smooth gameplay.
- Testing includes automated scripts and custom scenarios.
