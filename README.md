# BIT504_AT2_Task2
experiment_3
Changes to source code:
BOARD
hasWon method - checks reverse diagonal for 3 in a row.

GAMEMAIN
mouseClicked method - add repain method to redraw the graphics on the User Interface.

Tic Tac Toe source code is functioning.

experiment_2
Changes to Source Code:
GAMEMAIN
Add MouseEvent on MouseClicked event listener to 'this'.
Create instance of Board class called Board.
Call initGame method to initialise the game board.
Create new GameMain panel and add it to the frame.
Set the default close operation of the frame to exit_on_close.
Status bar to display messages - X's turn and O's turn.
Check which player has won and update currentstate.
When game is a draw set the currentstate to the draw gamestate.

CELL
Initialise variables row, col.
Call method clear() to sets the cell content to empty.
Set the value of content to Empty.

BOARD
Initialise the cells array.
Check whether the game has ended in a draw.
Correct spelling of constant GRID_WIDTH_HALF.

GAMESTATE
Create the enumeration for the variable GameState currentState.

