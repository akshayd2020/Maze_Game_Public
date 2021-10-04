# Maze_Game

<h2>Note: The code for this maze game has been privated in compliance with the Funadamentals of Computer Science 2 class. Please email at dupuguntla.a@northeastern.edu for full access to code.</h2>

![maze_image][maze.png]

This program was made to practice working with graphs and graph algorithms by designing mazes using Kruskal's algorihm and then solving them using breadth- or depth-first searches. The creation of the mazes and the solution of the mazes can be animated. 

USER GUIDE:
 - Run this program to create an example maze:
 - to create a custom maze, follow the instructions above the testBigBang method in the ExamplesMazeWorld class
 - When the maze is created, you can click "s" at any time 
 to color every square with a gradient of colors to show how far it is from the start of the maze
 - You can click "e" at any time to color every square with a gradient of colors to show how far it is from the end of the maze
 - You can click "t" at any time to toggle the showing of the visited paths
 - You can click "r" at any time to restart the maze (new maze will be randomized again)
 - Once the maze is created/reset, you can click "b" to do bfs and "d" to do dfs on the maze
 - Once the maze is created/reset, you can click "p" to manually traverse the maze with arrow keys
 - Once the solution is found, the path will be highlighted in dark blue
 - To create a maze with a bias in a particular direction, create a mazeworld that either takes in a "h" for a horizontal bias or a "v" for a vertical bias and run BigBang on that
 - To show the construction of the maze, create a mazeWorld with its last input being true
 - and run bigBang with that
 
