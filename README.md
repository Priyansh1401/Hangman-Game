# Description

A simple React-based implementation of the classic Hangman game. Players try to guess the hidden word by suggesting letters one at a time. The game progresses by revealing the correct letters and drawing parts of the hangman figure for incorrect guesses.

# Features

- Interactive on-screen keyboard for letter selection.
- Automatically tracks and displays guessed letters.
- Displays the hangman figure progressively as incorrect guesses are made.
- Indicates win/loss states with an option to restart the game.

# Components
- App.tsx: The main component that manages the state of the game, including the word to guess, guessed letters, and win/loss logic. It renders the other components to form the complete game interface.

- HangmanDrawing.tsx: Responsible for rendering the hangman figure based on the number of incorrect guesses. The figure is built progressively, with each part of the body (head, body, arms, legs) appearing after each wrong guess.

- HangmanWord.tsx: Displays the word to be guessed. It shows correctly guessed letters and reveals the full word if the player loses.

- Keyboard.tsx: Handles the display and interaction of the on-screen keyboard. Allows players to guess letters by clicking buttons corresponding to each letter.

# Tech Stack
- React: A JavaScript library for building user interfaces.
- TypeScript: A superset of JavaScript that adds static typing to the language.
- CSS: Used for styling components.
- Node.js: JavaScript runtime environment used for building and running the application.
- npm: Package manager for Node.js, used to install dependencies.
