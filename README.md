# Battleship Game

## Overview

This is a CMD-based 2D Battleship game that I developed during my early stages of coding in 2020, while I was a freshman in university. This project is written in the C language and includes features such as random ship generation, form validation, and a user-friendly interface.

## Features

- **Ship Generation:**
  The game randomly generates ships of various sizes, ensuring they don't overlap and are logically placed within the 8x8 grid (A-H, 0-7).

- **Form Validation:**
  The ship creation process includes checks to prevent overlaps and ensure ships are within the valid grid range.

## Code Structure

### Structures

- **COORD:**
  Defines a structure for coordinates (X, Y) on the console.

- **koordinat:**
  Represents a structure to conveniently store coordinates.

### Functions

- **gotoxy(int x, int y):**
  Moves the cursor to the specified console coordinates (X, Y).

- **buildChart(char list[9][9]):**
  Creates the game chart, representing the 8x8 grid with coordinates (A-H, 0-7).

- **print(char list[9][9]):**
  Decorates the chart and interface of the game for a user-friendly experience.

- **createShips(koordinat gecicidizi[20]):**
  Generates ships of different sizes, ensuring logical placement and preventing overlaps.

- **welcomeScreen():**
  Displays the welcome screen when the game starts.

- **menu():**
  Displays the main menu for the player to navigate.

- **level():**
  Allows the player to choose the game level.

- **play():**
  Initiates the gameplay.

- **howtoplay():**
  Provides instructions on how to play the game.

- **credits():**
  Displays credits for the game.

- **gameOver():**
  Handles the game over scenario.

- **victory():**
  Handles the victory scenario.

- **shipDestroyedInfo():**
  Provides information when a ship is destroyed.

- **quit():**
  Allows the player to quit the game.

## Usage

To play the game, follow these simple steps:

1. Run the program.
2. Navigate through the main menu.
3. Choose a game level.
4. Enjoy the Battleship game experience.

## Acknowledgments

This Battleship game is a simple yet engaging project created during the learning process. Feel free to explore and contribute to enhance its features.
