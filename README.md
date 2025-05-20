This project implements a Genetic Algorithm (GA) to navigate a snake-like agent through a maze from a start point to an end goal. The AI learns to avoid walls and find the shortest path using evolutionary strategies.

Features:
Maze Navigation: A predefined 15x15 maze with walls and open paths.

Genetic Algorithm Implementation: Uses the DEAP library for selection, crossover, and mutation operations.

Path Visualization: Plots the best path found at key generations using matplotlib.

Custom Mutation: Ensures direction changes during mutation to promote diversity.

Fitness Evaluation: Combines goal-reaching success and Manhattan distance minimization
