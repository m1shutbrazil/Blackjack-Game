# Blackjack-Game# Blackjack Game

This is a simple terminal-based Blackjack game implemented in C++.

## Features

- Classic Blackjack game mechanics
- Playable in the terminal
- Dealer vs. Player gameplay
- Cards are dealt randomly from a standard 52-card deck
- Player can choose to hit or stand
- Dealer follows standard rules (must hit if total is 16 or below, stand if 17 or higher)
- Game automatically handles win/lose/draw conditions

## How to Play

- The goal of the game is to get as close to 21 as possible without going over.
- Both the player and dealer are dealt two cards to start.
- The player can then choose to:
  - Hit: Draw another card
  - Stand: Keep the current hand and end the turn
- The dealer must draw cards until their total is 17 or higher.
- The game ends when either the player or dealer busts (goes over 21) or both stand.

### Card Values

- Number cards (2-10) are worth their face value.
- Face cards (Jack, Queen, King) are worth 10 points.
- Aces can be worth either 1 or 11 points, depending on which is more beneficial.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Blackjack-Game-cpp.git
   cd blackjack-game-cpp
2. Compile the programm
   ```bash
   g++ -o Blackjack BlackJack.cpp
3. Run the game
   ```bash
    ./Blackjack
