# Wordle Game

This project is a simple implementation of the Wordle game using HTML, CSS, and JavaScript. Players guess a hidden word within a limited number of attempts, receiving feedback on their guesses.

## Features

- Dynamic game board creation using JavaScript.
- Interactive keyboard interface for letter input.
- Visual feedback for correct letters in correct positions (`●`), correct letters in wrong positions (`○`), and incorrect letters (`◻`).
- End-game conditions with win or loss feedback.

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/wordle.git
   cd wordle
   ```

2. **Open `index.html` in your web browser:**

   Simply open the `index.html` file in any modern web browser to play the game.

3. **Gameplay:**

   - You have 6 attempts (`height`) to guess the hidden word (`width` letters).
   - Click on the letters on the virtual keyboard to input your guesses.
   - Click `Enter` to submit your guess for evaluation.
   - Feedback will be provided after each guess indicating correct letters and their positions (`●`), correct letters in the wrong positions (`○`), and incorrect letters (`◻`).

## Files Structure

- **index.html**: Main HTML file that structures the game interface.
- **wordle.js**: JavaScript file containing game logic and functionality.
- **wordle.css**: CSS file for styling the game interface.

