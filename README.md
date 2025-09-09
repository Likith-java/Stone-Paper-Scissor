***

# Rock Paper Scissors

This is a simple implementation of the classic game "Rock Paper Scissors" using HTML, CSS, and JavaScript. The game allows a user to play against a computer opponent.

## How It Works

* **`index.html`**: This file sets up the structure of the game. It includes the title, three clickable choices (rock, paper, and scissors), a score display for the user and the computer, and a message area to show the result of each round.
* **`style.css`**: This file provides the styling for the game. It centers the content, sets up the layout for the choices and the scoreboard, and adds a hover effect to the choices.
* **`app.js`**: This is the core logic of the game.
    * It keeps track of the **user's score** and the **computer's score**.
    * When the user clicks on a choice, the `playGame` function is called.
    * The **computer's choice** is randomly generated.
    * The `showWinner` function determines the winner of the round based on the classic rules of the game.
    * The scores are updated, and a message is displayed to the user indicating who won or if it was a draw.

## How to Play

1.  Download or copy the three files: `index.html`, `style.css`, and `app.js`.
2.  Place all three files in the same folder.
3.  Open `index.html` in your web browser.
4.  Click on your desired move (rock, paper, or scissors) to play a round against the computer.
5.  The score will update, and a message will be displayed at the bottom of the screen.
