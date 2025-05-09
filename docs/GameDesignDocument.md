<!-- Markdown Docs: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax -->
## Unknown Glory Design Document

### Synopsis
You and another person wake up in a mysterious arena with no memory of how you got there. An unknown figure known as the Master appears and orders the two to fight—only one can escape alive.<br>

With no choice, you must battle to be the last one standing.

### Characters
There are 3 different characters, each with unique stats and abilities
- Knight: high attack and defense but low range
- Rogue: high mobility but difficult hitbot
- Archer: high range but low defense

### Cards
Each player has 13 cards with different deck based on the character.<br>
The card is displayed with cost, hitbox, and value.<br>
When card is executed, players that are stand on the hitbox relative to the caster's position are affected.
- 2 of each movement (up, down, left, right)
- 1 basic attack
- 3 special attack
- 1 block

### Resources
Energy
- Energy to use special cards
- Start with 1, gain 1 every round, maximum of 4
- If insufficient energy, executed card does nothing

Rereoll
- Use to reroll 5 random cards
- Start with 1, gain 1 every round, maximum of 2
- Return cards to the deck, shuffle, then redraw

### GamePlay
1. Do a coin flip. Winner becomes the Priority Player for the round
2. Shuffle the cards. Each player draws 5 random cards, then selects 3 cards or reroll. Set 3 cards in order.
3. Reveal and execute cards in order: Priority → Non → Priority → Non → Priority → Non
4. Switch Priority Player. Repeat from step 2 until one person run out of HP.

## Change Log
- Reroll count gain was changed from every 2 round from 1 round. This was to allow players to have more control of the gameplay and rely slightly less on luck
- Alot of the card damage was adjusted to balance out the difficulty of hitbox, cost, and damage
- Number of each movement card was increased from 1 to 2 to avoid players being stuck at a certain position.
- Priority players are only randomly selected at first and then switch on next round instead of randomly selecting every round. This was to allow players to be able to play more strategically and plan out their moves.

