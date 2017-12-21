Zakee Jabbar UIC


"Sudoku with Auto Solve"


This is a GUI version of the Sudoku Game. The game starts off with an empty board, and lets the user open a file in the resources folder which has information for a puzzle. The user can use the side bar to select a number to place in any spot. The user also has the option to clear spots on the board that weren't originally part of the puzzle. The user can also click on the "?" in the side panel and then click any cell on the board to view the candidate list of that cell.



Supported Functions:

File -> Load File : Loads a puzzle file
File -> Saves File : Save the current puzzle into a file
File -> Quit : Quits the game.
Hints -> Check on Fill : Enables a mode where it checks if the user placement is valid.
Hints -> Single : Resolves a spot using the Single Algorithm
Hints -> Hidden Single : Resolves a spot using the Hidden Single Algorithm
Hints -> Locked Candidates : Updates Candidate Lists using the Locked Candidate Algorithm
Hints -> Naked Pair : Updates Candidate Lists using the Naked Pairs Algorithm
Hints -> Solve All : Repeatedly uses the algorithms to resolve all spots.



To run this program on command line:

javac Game.java
java Game