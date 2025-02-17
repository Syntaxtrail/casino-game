# 🎰 Casino Game

> A sleek command-line casino experience where strategy meets fortune

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## ✨ Overview

Royal Casino Game is an engaging command-line gambling simulation that offers players a chance to test their luck with a simple yet exciting number-guessing mechanic. Start with a redeemable bonus and try your fortune across multiple rounds of play.

## 🎮 Game Features

- **Redemption System**: Begin your journey with a $500 bonus using code `ROYAL500`
- **Multiple Rounds**: Experience up to 5 thrilling rounds of play
- **Dynamic Betting**: Flexible betting system based on your current balance
- **Number Guessing**: Choose numbers between 1-10 for a chance to double your bet
- **Real-time Balance**: Track your winnings and losses as you play

## 🚀 Getting Started

### Prerequisites

- GCC Compiler
- C Standard Library
- Terminal or Command Prompt

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Syntaxtrail/casino-game.git
cd royal-casino
```

2. Compile the game:
```bash
gcc casino_game.c -o casino
```

3. Run the executable:
```bash
./casino
```

## 🎲 How to Play

1. **Launch**: Start the game and enter the redemption code `ROYAL500`
2. **Place Bet**: Enter your desired bet amount (must be within your current balance)
3. **Choose Number**: Select a number between 1 and 10
4. **Win/Lose**: 
   - Match the winning number to double your bet
   - Lose your bet amount if numbers don't match
5. **Continue**: Play up to 5 rounds or until your balance runs out

## 💡 Game Logic

```c
if (chosenNumber == winningNumber) {
    // Win condition: Double your bet
    *money += betAmount;
} else {
    // Lose condition: Lose your bet
    *money -= betAmount;
}
```

## 🎯 Features Breakdown

| Feature | Description |
|---------|------------|
| Redemption Code | Start with $500 bonus cash |
| Rounds | Maximum of 5 rounds per session |
| Betting Range | Flexible (1 to current balance) |
| Number Range | 1 to 10 |
| Win Multiplier | 2x bet amount |

## 🛠️ Technical Details

- Language: C
- Libraries Used:
  - `stdio.h`: Standard I/O operations
  - `stdlib.h`: Random number generation
  - `string.h`: String comparisons
  - `time.h`: Random seed generation

## 🔜 Future Enhancements

- [ ] Multiple game modes
- [ ] User profile system
- [ ] High score leaderboard
- [ ] Additional betting options
- [ ] Improved odds system
