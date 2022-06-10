# Artificiall-Intelligence-course

Programming exercises for CSE/MYY602 - Artificial Intelligence, Computer Science and Engineering University of Ioannina.

# UCS - Astar Algorithms

This programming exercise is about a labyrinth with obstacles, in which a robot have to navigate from the initial point to a final one. In order to 
achieve this goal it uses both algorithms to find the best solution. The UCS algorithm always find a full and best solution with exponential complexity of both time and space. 
This algorithm belongs to blind search algorithms. The Astar algorithm is based to a heuristic function, which expands the search frontier. 
If the heuristic function for every state n is smaller or equal to the actual distance, then the function is called admissible. Only then we can say that the method has a full and best path solution.
## How to run
```bash
    javac labyr.java
    java labyr
```

# Minimax Algorithm
This programming exercise is about a game with white and black cubes, in which a player plays with the computer, on who will take the most cubes.
The algorithm that was used in this game was Minimax Algorithm, with MAX the player and MIN the computer. On every turn, the player must take on cube away, while the computer does the same thing.
The first who collects all the cubes win. The game can also end with a draw.


## How to run
```bash
    javac Game.java
    java Game
```
