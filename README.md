# Indiana Jones and the Golden Idol Heist Simulator

This project was created to demonstrate my proficiency in the basics of C++. 
My favorite aspect of the source code is how the game board is managed as a single pointer 
that points to other allocated arrays of space pointers that each represent a space that is 
randomly assigned on each game load. 

`Space*** array = new Space ** [rows];`

Another notable achievement comes from instantiating the Indiana character object on line 53 of game.cpp, allowing
for a single line of code that is simply

`Indiana Jones;`

Use Indy's items to get the golden idol without dying.

Includes an intermediately sophisticated GNU makefile. Clone the repo, compile on Linux with `make`, and play with 
`./TheGame`
