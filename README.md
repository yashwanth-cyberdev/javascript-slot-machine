Slot Machine Game 🎠

This is a simple command-line slot machine game written in JavaScript. Players can deposit money, place bets, and spin the reels to try their luck and win based on matching symbols.

Features ✨

Deposit money to start playing.

Choose the number of lines to bet on (1-3).

Place a bet amount per line.

Spin the slot machine.

Check if you’ve won and receive your winnings.

Option to play again or exit the game.

Game ends when your balance runs out.

How to Play 🕹️

Game Flow:

Deposit MoneyStart by entering the amount you want to deposit.Example: Enter a deposit amount: 100

Choose Number of LinesSelect how many lines you want to bet on (1-3).Example: Enter the number of lines to bet on (1-3): 2

Place Your BetEnter the amount you want to bet per line.Example: Enter the bet per line: 10

Spin the ReelsThe game randomly generates a grid of symbols (3x3). If the symbols on your selected lines match, you win!

Check WinningsIf all symbols on a line are the same, you win based on the symbol's value. Your winnings are added to your balance.

Play Again or ExitChoose whether to continue playing or exit the game.Example: Do you want to play again (y/n)?

Game OverThe game ends if your balance runs out.

Installation & Setup ⚙️

Install Node.jsEnsure that Node.js is installed on your system.

Clone or Download the Repository

git clone https://github.com/yashwanth-cyberdev/javascript-slot-machine.git
cd slot-machine-game

Install DependenciesThe game uses the prompt-sync library for user input. Install it by running:

npm install prompt-sync

Run the GameStart the game by running:

node slot-machine.js

Rules 🔄

Each symbol has a value:

A: 5

B: 4

C: 3

D: 2

Winning Condition:A line is considered a win if all the symbols on that line are the same.

Winnings Calculation:Winnings = Bet Amount × Symbol Value

Bet Limits:

You cannot bet more than your balance.

You cannot bet more than your balance divided by the number of lines.

Example Gameplay 🕹️

Enter a deposit amount: 100
Enter the number of lines to bet on (1-3): 2
Enter the bet per line: 10

Spinning the reels...
C | A | B
B | B | B
A | A | C

You won $40!
Do you want to play again (y/n)? y

Technologies Used 🛠️

JavaScript: Core language for the game logic.

Node.js: Runtime environment.

prompt-sync: For handling user input.

Contributing 🤝

Feel free to fork this repository and submit pull requests to add new features, improve the game, or fix any bugs.

License 📄

This project is licensed under the MIT License. You’re free to use, modify, and distribute this game as you like.

Author ✍️

Developed with ❤️ by yashwanth-cyberdev
