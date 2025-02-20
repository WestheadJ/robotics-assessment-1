# Assignment 1

Link to the [video](https://youtu.be/rNhS-SPZXBo)

## Stage 1 - Get to the end
In the file [ ``` Fleming's Left Hand Rule.vrpython ```](https://github.com/WestheadJ/robotics-assessment-1/blob/base/Fleming's%20Left%20Hand%20Rule.vrpython) 
the program uses the Fleming's Left Hand Rule as a maze solving algorithm. It works by these simple steps:
- Look left
- If you can turn left turn left
- If not turn right

This gets you to the end of the maze, by using the ```down_eye``` it detects if the end is ```RED```

## Stage 2 - Get back to the start
In the file [```Advanced Maze Solver.vrpython```](https://github.com/WestheadJ/robotics-assessment-1/blob/base/Advanced%20Maze%20Solver.vrpython) the program
continues to use the afformentioned left hand rule however adds each movement to an array, then when at the end, the bot will reverse through the array and do the opposite until it reaches the start. It draws out it's path too and produces a very basic and very abstract matrix of it's path and then also outputs all of it's moves

## Stage 3 - Map the Maze and Return Shortest/Quickest Path
In the file [```VEXCODE_Map.vrpython```](https://github.com/WestheadJ/robotics-assessment-1/blob/5e9e9b03ffd3320140b818fcaa3eda4da6b90794/VEXCODE_Map.vrpython) was my attempt at making the bot go around all of the maze. Creating a new node for each movement by scanning it's surroundings, add them to a stack. It would mark it's surroundings as either an unvisited path, a visite path, or a wall. However my pointers for backtracking messed me up and I ended up running out of time to figure out my pointer error, but equally my fault for not asking for help on understanding my error.



