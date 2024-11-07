# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
The most difficult part was implementing the has_won function since it's tedious to check through the whole array for a vertical, horizontal, or diagonal win

2. Explain how you would add a computer player to the game.
To add a computer player to the game, I add methods for the computer to pick random spot that has not be chosen to put their mark and then prompt the user for their move.

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
It may look at the entire board and search for rows, columns, or diagonals where the human player already has 2 marks and make their move in the 3rd spot to block the user from winning. It could also involve a small machine learning model that's trained on tic tac toe games in order to better predict the user's actions and potentially win a game.