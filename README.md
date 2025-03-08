# In this project, I have implemented an AI-controlled Snake game using Pygame. The snake (represented by a green rectangle) will navigate through a grid to find food (represented by a red rectangle). Obstacles (represented by brown rectangles) will be randomly placed in the grid depending on the difficulty level. The AI must decide the best path to reach the food before the timer runs out. I have implemented different path finding algorithms and compare their performance.

The game consists of a grid-based environment where:
The snake moves automatically based on a chosen algorithm.
The food and obstacles are placed at the beginning and remain fixed.
The game ends when:
The timer runs out. Initially set to 30 seconds.
The snake collides with an obstacle or walls of the maze.
The game is separated into two files:
snake.py: Contains the main game loop and environment setup. You mustn’t make changes in this file.
search_algorithms.py: Contains different search algorithms for path finding. You are needed to implement these search algorithms.
The game supports four levels with increasing obstacle density:
Level 0: No obstacles.
Level 1: Low obstacle density.
Level 2: Medium obstacle density.
Level 3: High obstacle density.
The game supports multiple search algorithms:
Random Movement (Implemented): A basic algorithm implemented to give students an idea about what you need to do. It selects an action randomly out of all possible ones.
BFS (Need to implement)
DFS (Need to implement)
IDS (Need to implement)
UCS (Need to implement)
GreedyBFS (Need to implement)
A* (Need to implement)
