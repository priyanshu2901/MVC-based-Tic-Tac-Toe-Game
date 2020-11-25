# MVC-based-Tic-Tac-Toe-Game
This is a project in which the replica of tic tac toe game is build in python, it follows the MVC architecture.

Responsibility of view_tictactoe:
In this everything is drawn on the canvas using Tkinter. It takes the attributes from the model_tictactoe.py file

Responsibility of model_tictactoe:
In this, we implement a class name Board with the necessary methods and variables.
The method that is implemented in this is : 
isWin(): check whether anyone wins or not
isTie(): check whether the game is tied or not
update(): update the player move
reset(): It will reset the game

Responsibility of controller_tictactoe
In this event, handling is done for all the button and it calls the CreateBoard function defined in the view_tictactoe.py file.
