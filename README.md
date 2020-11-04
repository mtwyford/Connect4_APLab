# Connect4_APLab

No Solution will be provided here 
- just a starting point and guide for students to:

*write a program that replicates game play of 6row x 7column board game
*players alternate turns to 'drop' pieces by column number into the next position
*Students should choose a datatype for the 2D Array they are comfortable working with
  *Does printout of board help user to see layout easily?
  *Is it easy to tell where pieces have been placed?
  *Does the 'empty' space confuse the player?

The most challenging part of this task is determining when a player has placed a winning piece, hence:
  *Students should code the game to use methods when possible that run within conditions
  *Play will continue until a winner had been called (4 in a row)
    * A win can be four across, 4 up or down, or 4 diagonally
    *Recommend students try vertical and horizontal first
  *In this case, think of the sequence of the game play
  * P1 -> CheckWin -> P2 -> CheckWin, repeat
  
