# Monstersweeper

Monstersweeper is a Minesweeper-inspired RPG game where you defeat weak monsters, level up, and ultimately clear all monsters to win the game. Here are the detailed mechanics and instructions for the game:

---

## Game Mechanics

- **Core Concept**:
  - Similar to Minesweeper, but when you open a blank cell, the displayed number indicates the sum of the levels of monsters surrounding the cell.

- **Combat**:
  - Combat begins when you open a cell containing a monster.
  - You attack first, dealing damage equal to your level to the monster.
  - If the monster survives, it counterattacks, dealing its level's worth of damage to you.
  - The battle continues until either you or the monster is defeated, and this process occurs instantaneously.
  - Monsters at or below your level can be defeated without taking damage.

- **Special Modes**:
  - **BLIND** and **HUGE x BLIND** Modes:
    - In these modes, you cannot defeat monsters.
    - The goal is to open all non-monster cells to clear the level.

---

## Controls

- **PC**:
  - Click on a cell with the mouse to open it.
  - Click on a monster to toggle the displayed value between its level and the sum of levels of adjacent monsters.
  - Press number keys over unopened cells to mark them.

- **Mobile**:
  - Tap on a cell to open it.
  - Tap on a monster to toggle the displayed value between its level and the sum of levels of adjacent monsters.
  - Press the level button at the bottom of the screen to enter marking mode, then mark any desired cell.
  - Use drag gestures for scrolling and pinch gestures to zoom in or out.

---

## Indicators

- **HP (Hit Points)**: Your life value; if it reaches zero, the game is over.
- **LV (Level)**: Indicates your level, which determines the damage you deal to monsters.
- **EX (Experience)**: Accumulates as you play; gaining enough experience levels you up.
- **NE (Next Experience)**: The experience required to reach the next level.
- **T (Time)**: Shows the elapsed time in the game.

---

## Additional Information

- **Inspiration**:
  - This game is inspired by the design from [this blog post](https://thewrongtools.wordpress.com/2015/08/31/cellsweeper-xlsm-dungeon-crawler-rpg-based-on-minesweeper/).

- **Development**:
  - The game is created using Excel VBA as a project for the NCKU VBA course.

- **Enhancements**:
  - This version introduces items, skills, and a shop system, along with modifications to the original design.

- **Usage**:
  - All materials are for academic purposes and not intended for commercial use.

---

Enjoy the challenge and strategy of Monstersweeper as you clear levels and defeat monsters!
