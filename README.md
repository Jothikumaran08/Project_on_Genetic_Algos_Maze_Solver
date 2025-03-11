# Project_on_Genetic_Algos_Maze_Solver
This project leverages Genetic Algorithms to solve maze problems efficiently. The algorithm simulates natural selection by evolving a population of potential solutions until an optimal or near-optimal path through the maze is found.

Dataset Description

The maze environment is represented as a grid where:

0 denotes an open path.

1 denotes a wall or obstacle.

The starting point and the goal are predefined within the grid.

New features developed include:

Maze Encoding: Encoding maze grids for algorithm input.

Fitness Function: Evaluates each path's efficiency and correctness.

Selection, Crossover, and Mutation: Core genetic operations to evolve solutions.

Data Cleaning Explanation

The maze grid was processed to ensure valid entries (only 0 and 1 values).

Path data was structured for compatibility with the Genetic Algorithm workflow.

Genetic Algorithm Process

Population Initialization: Randomly generated potential paths.

Fitness Evaluation: Calculated based on path length, obstacle avoidance, and closeness to the goal.

Selection: Fittest individuals are chosen to breed.

Crossover and Mutation: Techniques to diversify and improve path efficiency.

Termination: Algorithm stops after reaching a defined number of generations or finding an optimal solution.

Visualizations for Key Insights

1. Maze Visualization

Displays the maze grid with the starting point, goal, and optimal path.

2. Fitness Score Plot

A line graph tracking fitness scores across generations, showing algorithm improvements.

3. Optimal Path Highlight

Visual depiction of the shortest or most effective path discovered by the algorithm.
