# Business Board Game

A property-and-money strategy board game for 4 players, built for the browser. Players roll the dice, move around the board, buy properties, pay rent, manage loans, and try to finish with the highest total value.

## How to Play:https://kaushalch1.github.io/business/

Open the help page first, then start the game.

1. Open `indexi.html`.
2. Click **Play Game** to go to `index.html`.
3. Click the dice button to roll.
4. Follow the result on the board.
5. Use **Buy** or **Rent** when the game asks you to.
6. Try to grow your money and property value while avoiding heavy loans.

## Game Goal

The goal is to become the richest player by the end of the game.

Final score is based on:

- current balance
- property value
- loan due

The player with the highest total wins.

## Players and Turns

- The game has 4 players: Player 1, Player 2, Player 3, and Player 4.
- Players take turns in order.
- The current player's card is highlighted.
- If a player rolls 6, they get one extra turn.

## Board Rules

- Passing GO gives the player ₹10000.
- Rest House gives a bonus of ₹11000.
- Club costs ₹4000.
- Jail sends the player to jail for 2 turns.
- Tax and Wealth Tax squares reduce money.
- If a property is free, it can be bought.
- If another player owns the property, rent must be paid.

## Buy and Rent

- Press **Buy** to purchase the property you land on, if it is available.
- Press **Rent** when rent needs to be paid.
- Rent goes to the player who owns the property.
- If the square belongs to the bank, the bank receives the money.

## Loans

- Press **Take Loan** to borrow ₹10000.
- A player can only take a loan if they do not already have one.
- The loan amount is shown in red.
- The player's current balance is shown in green.
- Loan grows with interest over time.
- In this game, every 5 turns the loan increases by 10%.
- Press **Pay Loan** when the player has enough balance to clear it.

## Special Squares

- **GO**: gives money when passed.
- **Jail**: skips the next 2 turns.
- **Rest House**: gives bonus money.
- **Club**: removes money.
- **Tax**: deducts money.
- **Wealth Tax**: deducts money.
- **Community Chest**: special board square.

## End of Game

The game ends when all purchasable cards are bought.

When the game ends, a popup shows:

- Player
- Loan
- Assets
- Current Balance
- Total

The players are sorted by total score, highest first, and the top player is declared the winner.
## Tech Stack

- HTML for structure
- CSS for layout and styling
- JavaScript for gameplay logic
<img width="1596" height="897" alt="image" src="https://github.com/user-attachments/assets/3ff7ca35-6b51-48b6-b0c6-ae7ba5edbf01" />
