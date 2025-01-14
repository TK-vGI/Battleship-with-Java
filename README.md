# Battleship-with-Java
Tutorial project for Java programming
Battleship (also called Battleships or Sea Battle) is a two-player strategy game whose history traces back to the First World War. It started off as a pencil and paper game, until Milton Bradley coined the rules and published the game. Fun fact: it was one of the first games to be produced as a computer game in 1979! In this project, we will recreate this timeless classic.

First off, brush up on the rules of the game. There are different variations of the Battleship game, but we will stick to the original rules written by Milton Bradley. You have a 10×10 game field and five ships to arrange on that field. The ships can be placed horizontally or vertically but not diagonally across the grid spaces; the ships should not cross or touch each other. The goal is to sink all the ships of the opponent before your opponent does this to you.

Understanding how the ships will be fielded is exactly where we are going to start!

Before you start, let's discuss the conventions of the game:

    On a 10x10 field, the first row should contain numbers from 1 to 10 indicating the column, and the first column should contain letters from A to J indicating the row.
    The symbol ~ denotes the fog of war: the unknown area on the opponent's field and the yet untouched area on your field.
    The symbol O denotes a cell with your ship, X denotes that the ship was hit, and M signifies a miss.

Stage 1/6:Create the field
Stage 2/6:Place all ships
Stage 3/6:Add shooting functionality
Stage 4/6:Implement the "fog of war" feature
Define rules to end the game
Stage 6/6:Add multiplayer option
