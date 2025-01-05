# Slot Machine Game 🎠

This is a simple **command-line slot machine game** written in JavaScript. Players can deposit money, place bets, and spin the reels to try their luck and win based on matching symbols.

---

## Features ✨

1. Deposit money to start playing.
2. Choose the number of lines to bet on (1-3).
3. Place a bet amount per line.
4. Spin the slot machine.
5. Check if you’ve won and receive your winnings.
6. Option to play again or exit the game.
7. Game ends when your balance runs out.

---

## How to Play 🕹️

### Game Flow:

1. **Deposit Money**  
   Start by entering the amount you want to deposit.  
   Example: `Enter a deposit amount: 100`

2. **Choose Number of Lines**  
   Select how many lines you want to bet on (1-3).  
   Example: `Enter the number of lines to bet on (1-3): 2`

3. **Place Your Bet**  
   Enter the amount you want to bet per line.  
   Example: `Enter the bet per line: 10`

4. **Spin the Reels**  
   The game randomly generates a grid of symbols (3x3). If the symbols on your selected lines match, you win!

5. **Check Winnings**  
   If all symbols on a line are the same, you win based on the symbol's value. Your winnings are added to your balance.

6. **Play Again or Exit**  
   Choose whether to continue playing or exit the game.  
   Example: `Do you want to play again (y/n)?`

7. **Game Over**  
   The game ends if your balance runs out.

---

## Installation & Setup ⚙️

1. **Install Node.js**  
   Ensure that [Node.js](https://nodejs.org/) is installed on your system.

2. **Clone or Download the Repository**

   ```bash
   git clone https://github.com/yashwanth-cyberdev/javascript-slot-machine
   cd slot-machine-game
   ```

3. **Install Dependencies**  
   The game uses libraries mentioned in package.json to install libraries run:

   ```bash
   npm install
   ```

4. **Run the Game**  
   Start the game by running:
   ```bash
   node game.js
   ```

---

## Rules 🔄

1. Each symbol has a value:

   - **A**: 5
   - **B**: 4
   - **C**: 3
   - **D**: 2

2. Winning Condition:  
   A line is considered a win if all the symbols on that line are the same.

3. Winnings Calculation:  
   Winnings = Bet Amount × Symbol Value

4. Bet Limits:
   - You cannot bet more than your balance.
   - You cannot bet more than your balance divided by the number of lines.

---

## Example Gameplay 🕹️

```plaintext
Enter a deposit amount: 100
Enter the number of lines to bet on (1-3): 2
Enter the bet per line: 10

Spinning the reels...
C | A | B
B | B | B
A | A | C

You won $40!
Do you want to play again (y/n)? y
```

---

## Technologies Used 🛠️

- **JavaScript**: Core language for the game logic.
- **Node.js**: Runtime environment.
- **prompt-sync**: For handling user input.

---

## Author ✍️

Developed with ❤️ by [Yashwanth](https://github.com/yashwanth-cyberdev)
