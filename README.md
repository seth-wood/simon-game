# Simon Game

A web-based implementation of the classic Simon memory game. Players must replicate a sequence of colors, which gets longer with each round. The game provides audio-visual cues to help players remember the sequence.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies](#technologies)
- [File Structure](#file-structure)
- [How to Play](#how-to-play)
- [Contributors](#contributors)
- [License](#license)

## Introduction
The Simon game is a memory skill game where the player must repeat random sequences of lights and sounds. Each round adds a new step to the sequence, making it progressively harder.

## Installation

### Prerequisites
To run the Simon game locally, you will need:
- A modern web browser (Chrome, Firefox, etc.)
- A basic web server (optional, but recommended for best performance)

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/simon-game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd simon-game
   ```
3. Open `index.html` in your web browser.

Alternatively, you can host the game on any static website hosting service.

## Usage
Once you load the game:
- Press any key to start the game.
- Watch and listen to the sequence of lights.
- Click the buttons in the same order the lights flash.

If you get the sequence correct, you proceed to the next level, which adds another color to the sequence.

## Features
- Random color sequences that increase in difficulty.
- Visual and audio feedback for each button press.
- Game over state with an option to restart.

## Technologies
The project is built using:
- HTML
- CSS
- JavaScript
- jQuery

## File Structure
```plaintext
simon-game/
│
├── index.html        # The main HTML file
├── styles.css        # Styling for the game
└── game.js           # Game logic implemented in JavaScript
```

## How to Play
1. Press any key to start the game.
2. A sequence of colors will be displayed.
3. Repeat the sequence by clicking the colored buttons in the same order.
4. The sequence gets progressively longer with each level.
5. If you make a mistake, the game will show "Game Over" and prompt you to restart by pressing any key.

## Contributors
- [Your Name](https://github.com/your-username)

## License
This project is licensed under the MIT License.
