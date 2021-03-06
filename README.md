# Donsol

Donsol is a solitary card game, designed by John Eternal in which you must go through the deck in sequences of 4 cards.

<img src='https://raw.githubusercontent.com/hundredrabbits/Donsol/master/PREVIEW.jpg' width="600"/>

## Guide

A standard deck, jokers included, is a dungeon. Shuffle the deck and draw 4 cards, display them before you, this is a room. A room ends when all the cards are folded.

### ♥︎ Hearts Are Potions

Potion give you health points equal to their value, up to a maximum of 21 health points. Drinking multiple potions in a row will make you sick and result in no extra healing, only the first potion's value will be gained in HP. Potions are equal to their value and face cards (J,Q,K,A) each are equal to 11.

### ♦ Diamonds Are Shield

Shields absorb the damage difference from a monster's value. Shields can only defend against monsters in descending value and if you use a shield on a monster with higher or equal value to the previous, it will break. Broken shields leave you unarmored, and taking full damage. A shield card will replace a previously folded shield card. Shields are equal to their value and face cards (J,Q,K,A) each are equal to 11.

### ♣♠ Clubs And Spades Monster Cards

Monster cards are equal to their value, and face cards are as follows J is 11, Q is 13, K is 15, A is 17; Jokers are both equal to 21. You may escape a room, if you have not escaped the previous one or have handled all the monsters in the current room. When escaping, the remaining cards are shuffled back into the deck.

## Controls

### File
- New: `CmdOrCtrl+N`
- Open: `CmdOrCtrl+O`
- Save: `CmdOrCtrl+S`

### Edit
- Insert: `I`
- Copy: `CmdOrCtrl+C`
- Paste: `CmdOrCtrl+V`
- Undo: `CmdOrCtrl+Z`
- Delete: `Backspace`
- Move Up: `Up`
- Move Down: `Down`
- Move Left: `Left`
- Move Right: `Right`
- Deselect: `Esc`

### Stroke
- Line: `A`
- Arc: `S`
- Arc Rev: `D`
- Bezier: `F`
- Connect: `Z`

### Effect
- Thicker: `}`
- Thinner: `{`
- Thicker +5: `]`
- Thinner -5: `[`
- Linecap: `Y`
- Mirror: `Space`
- Fill: `G`

### View
- Tools: `U`
- Grid: `H`
- Control Points: `J`
- Expert Mode: `:`

<img src='https://cdn.rawgit.com/hundredrabbits/Donsol/master/LAYOUT.svg?v=1' width="600"/>

## Extras

- Download additional [themes](https://github.com/hundredrabbits/Themes).
- Support this project through [Patreon](https://patreon.com/100).
- See the [License](LICENSE.md) file for license rights and limitations (MIT).
