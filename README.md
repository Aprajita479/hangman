# Hangman Game

This is a simple Hangman game implemented in HTML, CSS, and JavaScript. The game allows players to guess a word by selecting letters and trying to complete the word before the man is fully drawn on the canvas.

## Usage

To play the Hangman game, follow these steps:

1. Open the `index.html` file in a web browser.
2. On the game screen, select a category by clicking on one of the option buttons (e.g., "fruits", "animals", "countries").
3. Once a category is selected, the game will choose a random word from that category.
4. The chosen word will be displayed as dashes on the screen.
5. Click on the letter buttons to guess letters in the word.
6. If the guessed letter is correct, it will replace the corresponding dash(es) in the word.
7. If the guessed letter is incorrect, a part of the hangman will be drawn on the canvas.
8. Keep guessing letters until the word is complete or the hangman is fully drawn.
9. If the word is complete before the hangman is drawn, you win the game.
10. If the hangman is fully drawn before the word is complete, you lose the game.
11. After winning or losing, a new game can be started by clicking the "New Game" button.

## Files

The code for the Hangman game is organized into the following files:

### `index.html`

This file contains the HTML structure of the game interface. It includes references to external CSS and JavaScript files, as well as the game elements such as buttons, canvas, and result text.

### `style.css`

This file contains the CSS styles for the game interface, including the layout, colors, and animations.

### `script.js`

This file contains the JavaScript code that handles the game logic. It initializes the game, generates words based on the selected category, handles button clicks, updates the word display, draws the hangman on the canvas, and determines the game outcome.

## Customization

You can customize the game by modifying the following parts of the code:

- **Options**: The game currently includes three categories ("fruits", "animals", "countries") with corresponding word lists. You can add or remove words from these lists or create new categories with your own word lists.

- **Styling**: The appearance of the game interface can be customized by modifying the CSS styles in the `style.css` file. You can change colors, fonts, sizes, and other visual elements to match your preferences.

## Compatibility

The Hangman game should work in modern web browsers that support HTML5, CSS3, and JavaScript.

Please note that the code provided here is a basic implementation of the Hangman game and may not include advanced features such as input validation, scoring, or multiplayer functionality. Feel free to enhance the game based on your requirements and imagination.

Have fun playing Hangman!
