# CI2025_lab3

### Proposed Solutions

- A* with euclidean distance for non-negative values
- Bellman-Ford for negative values, negative weight cycles are excluded.

Results of the algorithms are in the results folder in csv format in two separate files, one for negative and another for non-negatives values. Results are limited to problem size of 100 since the computational time is unfeasible for larger sizes.

csv header includes this params: 
`'size', 'density', 'noise_level', 'start', 'goal', 'astar_path', 'astar_cost', 'bellman_ford_path', 'bellman_ford_cost'`