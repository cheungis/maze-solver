# maze-solver
A program that uses DFS to see if a given maze is solvable.

Quick guide to building a maze.txt:
- First line represents the x,y dimensions of the maze.
- Second line represents coordinate for the start point.
- Third line represents coordinate for the end point.

After that the rest of lines repesent the legal moves possible within the maze.
eg if the file is:

x y

a b

c d

a b c d

Then it means that:
- the maze is x wide and y long.
- the start point is on block[a][b]
- the end point is on block[c][d]
- block[a][b] -> block[c][d] is legal, ie you can go from block[a][b] straight over to block[c][d].


Built using the Python language.
