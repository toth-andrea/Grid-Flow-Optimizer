# Grid-Flow-Optimizer
<!--C++/Qt puzzle solver where colored resources are produced, routed via conveyors, and delivered to consumers. Optimizes delivery time and conveyor usage while handling color mixing, collisions, and impossible cases.--!>

Grid Flow Optimizer is a C++ project built with Qt that simulates and solves a resource distribution puzzle on a grid.
The system contains producers that periodically generate colored units, consumers with specific needs, and conveyor belts that route resources.
The main challenge is to design an optimal conveyor layout that satisfies all consumers in the fewest possible rounds—or detect when no solution exists.

Features:

Input/output with custom map file format.

Producers with adjustable speeds and consumers with configurable demands.

Advanced color mixing rules (RGB → Yellow, Cyan, Magenta, White).

Collision handling for multiple items on the same cell.

Optimization criteria: minimize number of rounds, then minimize conveyor count.

Graphical Qt interface with optional animations to visualize solutions.

Robust handling of unsolvable configurations.
