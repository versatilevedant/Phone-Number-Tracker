# Blackjack Game (Python)

A simple, console-based **Blackjack** game built using **Python** where the player competes against the dealer to get a hand value closest to **21** without exceeding it.

---

## Features

- **Card Dealing**: The game deals cards to both the player and the dealer from a shuffled deck.
- **Bet Management**: Players place bets and the game manages their balance based on outcomes.
- **Player Actions**: Players can either "Hit" (get another card) or "Stand" (keep the current hand).
- **Dealer Logic**: The dealer follows standard Blackjack rules (e.g., must "Hit" if hand value is below 17).
- **Game Outcomes**: 
  - **Bust**: Exceeds 21.
  - **Win**: Closer to 21 than the dealer.
  - **Tie**: Same hand value as the dealer.
- **Replay Option**: After each round, the player can choose to replay or quit.

---

## How to Play

1. **Clone the repository** or download the code files.
2. **Run the `blackjack.py` file** in the terminal/command line.
3. Players will **place their bets** before the round starts.
4. Both the **player and dealer** are dealt two cards. The dealer has one card face-up.
5. Players can either **Hit** (draw more cards) or **Stand** (end their turn).
6. The **dealer plays automatically** according to predefined rules.
7. After each round, the outcome (Win/Loss/Tie) is displayed and the player is asked whether to **replay** or **quit**.

---

## Game Flow

1. **Place Bet**: Players start by placing their bets.
2. **Deal Cards**: Cards are dealt to both the player and the dealer.
3. **Player's Turn**: Player can "Hit" or "Stand".
4. **Dealer's Turn**: The dealer draws cards based on Blackjack rules.
5. **Outcome Check**: The game checks for Win, Loss, or Tie.
6. **Replay Option**: After each round, players can decide to **replay** or **exit**.

---

## Technologies Used

- **Python 3**: Used for game logic and player interactions.
- **Command-line Interface (CLI)**: The game is played in the terminal/command line.

---

## Installation

To run the game, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/blackjack.git
