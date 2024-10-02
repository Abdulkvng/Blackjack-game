
# 🎮 Blackjack Game in C++ 🃏

Welcome to **Blackjack** — a terminal-based card game implemented in C++! This project simulates the popular casino game where the goal is to beat the dealer by getting as close to 21 as possible without going over.

---

## 📋 Table of Contents
- [About the Game](#about-the-game)
- [Rules](#rules)
- [Features](#features)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Game Flow](#game-flow)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 About the Game

This is a **Blackjack** game coded in C++. The game allows a player to compete against a computer-controlled dealer, following the standard Blackjack rules. The game is played through the terminal and aims to simulate a realistic Blackjack experience by using random card draws from a virtual deck.

---

## 📜 Rules

1. The goal is to have a hand value closer to **21** than the dealer without exceeding 21.
2. Number cards are worth their face value.
3. Face cards (Jack, Queen, King) are worth 10 points.
4. Aces can be worth **1** or **11**, depending on which value is more beneficial for the hand.
5. Both the player and the dealer start with two cards. One of the dealer’s cards remains hidden until the end.
6. Players can choose to "Hit" (draw a card) or "Stand" (keep their current hand).
7. The dealer must hit until their hand is worth **17** or more points.

---

## 🌟 Features

- **Randomized deck shuffling** for each new game.
- **Multiple game rounds** in a single session.
- **Dealer AI** that follows standard Blackjack rules.
- **Real-time score calculation** for both the player and the dealer.
- **Terminal-based interface**, making it lightweight and easy to run.

---

## 🛠️ Installation

To get the game up and running on your local machine, follow these simple steps:

### Prerequisites
- You must have a **C++ compiler** installed (e.g., `g++`, `clang`).

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/blackjack-game-cpp.git
   cd blackjack-game-cpp
   ```

2. **Compile the code**:
   ```bash
   g++ -o blackjack main.cpp
   ```

3. **Run the game**:
   ```bash
   ./blackjack
   ```

---

## 🎮 How to Play

1. Start the game by running the executable.
2. You will be dealt two cards, and one of the dealer’s cards will be hidden.
3. Choose to either:
   - **Hit**: Draw an additional card.
   - **Stand**: Keep your current hand and let the dealer reveal their hand.
4. After you stand, the dealer will draw cards until they reach a score of 17 or more.
5. The game will then compare your hand and the dealer’s hand to determine the winner.
6. You can play multiple rounds, and your score will be tracked during the session.

---

## 🎲 Game Flow

- **Initial Deal**: Player and dealer each get 2 cards. One of the dealer’s cards is hidden.
- **Player’s Turn**: You can choose to either hit or stand.
- **Dealer’s Turn**: The dealer reveals their hidden card and continues to draw cards if the score is below 17.
- **End Game**: The game compares both hands and declares the winner. The player has the option to play another round.

---

## 🤝 Contributing

Feel free to submit pull requests to improve the game, fix bugs, or add new features. Here's how you can contribute:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Added a cool feature"`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

Enjoy the game, and good luck beating the dealer! 🃏🎉
