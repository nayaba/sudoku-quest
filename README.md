<img src="./assets/sudoku-quest.png">

# Sudoku Quest: The Quest for the Lost Numbers

## Introduction

**Sudoku Quest: The Quest for the Lost Numbers** is an engaging and immersive Sudoku puzzle game set in the mystical land of Numeria. In this game, you will embark on an epic journey to restore harmony by solving Sudoku puzzles scattered across various regions. Each puzzle you solve brings you closer to defeating the evil sorcerer Malignus and retrieving the ancient Sudoku Scrolls.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [How to Play](#how-to-play)
4. [Storyline](#storyline)
5. [Regions of Numeria](#regions-of-numeria)
6. [Controls](#controls)
7. [Allies](#allies)
8. [Screenshots](#screenshots)
9. [Contributing](#contributing)
10. [License](#license)

## Features

- **Multiple Difficulty Levels:** Choose from Easy, Medium, Hard, Expert, and Master levels.
- **Interactive Gameplay:** Fill in numbers, receive hints, undo moves, and check your solution.
- **Engaging Storyline:** Follow Arya’s quest through different regions of Numeria.
- **Progress Tracking:** See your progress with a completion percentage indicator.
- **Visual and Audio Effects:** Enjoy a visually stunning interface with soothing background music.
- **Responsive Design:** Play on any device with a responsive and intuitive design.

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/sudoku-quest.git
   ```

2. **Navigate to the project directory:**

   ```sh
   cd sudoku-quest
   ```

3. **Open the `index.html` file in your web browser:**
   ```sh
   open index.html
   ```

## How to Play

1. **Select Difficulty:** Choose your desired difficulty level.
2. **Start the Game:** Click the "New Game" button to generate a new puzzle.
3. **Fill in Numbers:** Click on an empty cell and enter a number (1-9).
4. **Use Hints:** Click the "Hint" button for assistance if you’re stuck.
5. **Check Solution:** Click the "Check Solution" button to verify your puzzle.
6. **Reset Game:** Click the "Reset" button to start over.
7. **Pause/Resume:** Click the "Pause" button to take a break and "Resume" to continue.

## Storyline

In Numeria, numbers hold magical powers that maintain balance. The evil sorcerer Malignus has stolen the ancient Sudoku Scrolls, causing chaos. As Arya, a brilliant mathematician, you must solve the puzzles and retrieve the lost numbers to restore harmony.

## Regions of Numeria

1. **Arithmetica Village:** Difficulty: Easy
2. **Algebraic Forest:** Difficulty: Medium
3. **Geometrica Mountains:** Difficulty: Hard
4. **Calculus Caverns:** Difficulty: Expert
5. **The Prime Palace:** Difficulty: Master

## Controls

- **Mouse Click:** Select cells and buttons.
- **Keyboard:** Enter numbers (1-9).

## Allies

- **Pythagoras the Sage:** Provides hints and guidance.
- **Euclidia the Guardian:** Offers protective charms and magical artifacts.
- **Fibonacci the Healer:** Helps recover from mistakes with healing potions.

## Screenshots

![Main Menu](screenshots/main_menu.png)
![Game Board](screenshots/game_board.png)
![Victory Screen](screenshots/victory_screen.png)

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy your journey through Numeria and have fun solving puzzles in **Sudoku Quest: The Quest for the Lost Numbers**! If you have any questions or need support, please feel free to contact us.

---

### User Stories

- As a user, I want to start a new game, so that I can play Sudoku.
- As a user, I want to select the difficulty level of the sudoku game, so that I can play at my desired skill level.
- As a user I want to fill in numbers on the sudoku board, so that I can solve the puzzle.
- As a user, I want to see an indication if I enter an incorrect number so that I can correct my mistake.
- As a user, I want to be able to reset the game, so that I can start over if I make too many mistakes.
- As a user, I want to get hints so that I can receive help if I'm stuck.
- As a user, I want to be able to undo my last move, so that I can correct mistakes.
- As a user, I want to see a timer, so that I can track how long it takes me to solve the puzzle.
- As a user, I want to pause the gae, so that I can take a break and resume later.
- As a user, I want the game to verify my solutions so that I can know if I hae solved the puzzle correctly.
- As a user, I want to see a congratulatory message when I solve the puzzle, so that I feel accomplished.

### Pseudocode

```js
// A "New Game" button that, when clicked, generates a new Sudoku puzzle.
// The Sudoku board is displayed with some cells pre-filled according to the difficulty level chosen.

// Options for selecting difficulty levels (e.g., Easy, Medium, Hard).
// The number of pre-filled cells varies based on the selected difficulty level.

// The ability to click on an empty cell and enter a number (1-9).
// Only valid numbers (1-9) can be entered in the cells.

// When a number is entered, the game checks if it's a valid move.
// Invalid numbers cause the cell to be highlighted in red.

// A "Reset" button that clears the current board and starts a new game.

// A "Hint" button that fills in a correct number in one of the empty cells.

// An "Undo" button that removes the last entered number.

// A timer that starts when the game begins and stops when the puzzle is completed.

// A "Pause" button that stops the timer and disables board interactions.
// A "Resume" button that restarts the timer and enables board interactions.

// A "Check Solution" button that validates the entire board and indicates if the solution is correct.

// A message or animation that appears when the puzzle is solved correctly.
```
