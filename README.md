## Overview

This JavaScript Slot Machine project follows a tutorial from the Tech With Tim YouTube channel. Players can deposit, bet on multiple lines, spin the slots, and receive winnings.

## Dependencies

- Node.js ( `v14+` recommended )

## Gameplay

- **Deposit**: Enter a valid amount to add to your balance.
- **Lines:** Choose the number of active lines for potential wins.
- **Bet:** Enter a valid bet amount per line.
- **Spin:** Watch the reels spin with random symbols.
- **Wins:** Matching symbols across active lines award win amounts based on the paytable:
  
  - A: $5
  - B: $4
  - C: $3
  - D: $2

- **Play Again:** Choose to continue playing with your adjusted balance.

## Customization

- Modify `SYMBOLS_COUNT` and `SYMBOLS_VALUES` in `index.js` to create your own set of symbols and win payouts.
- Consider adding visual enhancements (libraries/frameworks) for a more immersive experience.

## Running the Game

- Open your terminal and navigate to the project directory.
- Run `node index.js`
