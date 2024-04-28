# TicTacToe Game

## Description:
The TicTacToe class serves as the main class for the game, creating a GUI window using JFrame to display the Tic-Tac-Toe grid and buttons (jb1 to jb9) for player interaction.

## Functionality:
Each button is assigned an ActionListener to respond to user clicks. Upon a click, the actionPerformed method is invoked, determining the current player's symbol (X or O) based on the count of moves. The clicked button updates with the player's symbol and disables further clicks. The winningPossibilities method checks for winning combinations (horizontal, vertical, and diagonal) on the grid. If a winning combo is found, the whoWins method displays a message indicating the winner. If no winning combo is detected after all moves, the game is declared a draw.

## Java Concepts:
Swing GUI: Utilizing Swing components (JFrame, JButton) to create the game's graphical interface.
Event Handling: Implementing the ActionListener interface for event handling, executing actions upon button clicks.
Conditional Statements: Using conditional statements (if and else if) to determine winning combinations and game outcomes.
Object-Oriented Programming (OOP): Demonstrating OOP principles by encapsulating functionality within methods and utilizing objects (JFrame, JButton) to represent game components.
