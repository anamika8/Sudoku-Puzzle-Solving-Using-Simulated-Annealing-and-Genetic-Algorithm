# Sudoku Puzzle Solving Using Simulated Annealing and Genetic Algorithm

This project presents two approaches to solving Sudoku puzzles—Simulated Annealing (SA) and Genetic Algorithm (GA)—and compares their efficiency across various difficulty levels.

## Project Overview:

- **Simulated Annealing**: A probabilistic technique that mimics thermodynamic processes. The algorithm makes moves based on a cost function and gradually cools down, leading to an optimal solution.
  - *Efficiency*: SA solved all puzzles efficiently, with minimal reheating.
  - *Tools*: Python, PyCharm, Matplotlib, Pygame.

- **Genetic Algorithm**: Utilizes population-based methods and evolutionary techniques like crossover and mutation to evolve solutions. The fitness function ensures uniqueness in rows, columns, and grids.
  - *Efficiency*: GA required more iterations than SA, often getting stuck in local minima.
  - *Tools*: Python, Pygame.

## Key Features:
- **Difficulty Levels**: Puzzles include easy, medium, hard, and evil, with a randomly generated puzzle for testing.
- **Comparative Results**: SA outperformed GA in terms of speed and accuracy, requiring fewer iterations to solve puzzles across all difficulty levels.

## Results:
- **SA**: Efficient across all puzzle levels, with a maximum solution time of 10 minutes.
- **GA**: Time-consuming, with suboptimal results due to local minima traps, requiring additional iterations and tuning.

## Future Directions:
Further exploration of Constraint Satisfaction Problems (CSP) could enhance the comparison of these algorithms. A controlled environment may also offer more accurate performance metrics for SA, GA, and CSP.

## Conclusion:
Simulated Annealing proved more efficient than Genetic Algorithm, showing faster and more consistent results. Fine-tuning GA hyperparameters and adding a restart heuristic could improve its performance in future implementations.

## References:
- [Simulated Annealing Code](https://github.com/anamika8/Sudoku-Puzzle-Solving-Using-Simulated-Annealing-and-Genetic-Algorithm/blob/main/Simulated_Annealing_Sudoku.ipynb)
- [Genetic Algorithm Code](https://github.com/anamika8/Sudoku-Puzzle-Solving-Using-Simulated-Annealing-and-Genetic-Algorithm/blob/main/Genetic_Algorithm.ipynb)

