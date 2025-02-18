# Assignment 1

## Stage 1 - Get to the end
In the file [ ``` Fleming's Left Hand Rule.vrpython ```](https://github.com/WestheadJ/robotics-assessment-1/blob/base/Fleming's%20Left%20Hand%20Rule.vrpython) 
the program uses the Fleming's Left Hand Rule as a maze solving algorithm. It works by these simple steps:
- Look left
- If you can turn left turn left
- If not turn right

This gets you to the end of the maze, by using the ```down_eye``` it detects if the end is ```RED```

## Stage 2 - Get back to the start
In the file [```Advanced Maze Solver.vrpython```](https://github.com/WestheadJ/robotics-assessment-1/blob/base/Advanced%20Maze%20Solver.vrpython) the program
continues to use the afformentioned left hand rule however adds each movement to an array, then when at the end, the bot will reverse through the array and do the opposite
until it reaches the start.

