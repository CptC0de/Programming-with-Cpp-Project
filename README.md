## Programming-with-Cpp-Project
# Maze Solver (not ccomplete)
The Maze Solver is a C++ program that navigates through a maze using a depth-first search algorithm. 
The maze consists of various cell types, such as empty cells, walls, starting and goal positions,
boosters (e.g., goggles, speed potion), hurdles (e.g., fog, slowpoke potion), and the agent itself.

# Features
Depth-first search algorithm for maze navigation.
Ability to handle boosters and hurdles.
Visualization of the maze with the agent's movements.
Display of the final path taken by the agent.
Calculation of the final score achieved by the agent.

# File Format
The maze file should be a text file where each character represents a cell type:

0: Empty cell
1: Wall
2: Starting position
3: Goal position
4: Goggles (booster)
5: Speed Potion (booster)
6: Fog (hurdle)
7: Slowpoke Potion (hurdle)
8: Agent

# Used Maze Design
2 0 0 0 1 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 1

1 0 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 1

1 1 0 0 0 5 0 0 0 6 0 0 0 1 0 0 0 0 0 0 1

1 1 0 1 7 1 0 1 0 1 0 1 0 1 4 1 0 1 0 1 0

1 1 5 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0

1 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0

1 1 0 1 0 0 0 1 0 0 0 1 0 0 0 1 0 0 0 1 0

1 1 0 1 0 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 0

1 1 0 1 0 1 0 0 0 1 0 0 0 0 0 0 0 0 0 1 0

1 1 6 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0

1 1 0 1 0 1 0 1 0 0 0 1 0 1 0 0 0 1 0 1 0

1 1 0 1 0 1 7 1 1 1 1 1 0 1 1 1 1 1 1 1 0

1 1 0 1 0 1 0 1 0 0 0 0 0 6 0 0 0 0 0 1 0

1 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0

1 1 0 1 6 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0

1 1 0 1 0 1 0 1 5 1 0 1 0 1 0 1 7 1 0 1 0

1 1 0 1 0 5 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0

1 1 0 1 0 1 0 1 0 0 0 1 0 0 0 0 0 0 0 1 0

1 0 0 0 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 1

1 1 1 0 0 0 0 0 0 1 1 1 1 1 1 1 1 0 0 0 3

0 1 1 0 0 1 1 1 1 1 0 0 0 0 0 0 0 0 0 1 1
