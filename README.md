# 🧠 Simon Game (Color Memory Game)

This is a simple color sequence memory game inspired by Simon game. The goal is to memorize and repeat the sequence of colors as it grows longer with each level.

## 🎮 How to Play

-   Press any key to start the game

-   A color will flash — remember it

-   Click the color buttons in the same order

-   With each level, a new color is added to the sequence

-   If you make a mistake, the game ends and your score (level) is shown

-   Press any key to restart

## Featues

-   Random color sequence generation

-   User and game sequences tracked and compared

-   Visual feedback using flashing effects

-   Score display on game over

-   Simple and responsive design

## Play the Game

Visit this page to play the game. Have fun!

![Simon Game](https://koustav2908.github.io/simon-game/)

## Technologies Used

-   HTML
-   CSS
-   JavaScript

## 📁 Project Structure

-   `index.html` – Main structure and buttons

-   `style.css` – Styling for buttons and animations

-   `script.js` – Core game logic

## 🧪 Game Logic Overview

-   The game maintains two arrays:

    -   `gameSeq` – the correct sequence

    -   `userSeq` – the player's input

-   On each level, a new color is randomly added to the `gameSeq`

-   When the user clicks a button, it's checked against the `gameSeq`

-   If the full sequence matches, the game moves to the next level

-   On mismatch, the game resets and displays the score

## 🚀 Getting Started

To run the game locally:

1. Clone or download the project

2. Open `index.html` in your browser

3. Start playing!
