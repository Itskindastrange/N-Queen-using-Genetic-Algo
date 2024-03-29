N-Queens Solver using Genetic Algorithm

This Python project implements a genetic algorithm solution to the classic N-Queens problem. The goal is to place N chess queens on an N x N chessboard without any queens attacking each other.

Core Functions

* **`random_chromosome(size)`:** Generates a random chromosome (potential solution).
* **`fitness(chromosome)`:** Evaluates the fitness of a chromosome (fewer queen collisions = higher fitness).
* **`probability(chromosome, fitness)`:** Calculates the probability of a chromosome being selected for reproduction.
* **`random_pick(population, probabilities)`:** Selects a chromosome based on its probability.
* **`reproduce(x, y)`:** Combines two chromosomes (crossover) to create a new offspring.
* **`mutate(x)`:** Introduces a small random change to a chromosome (mutation).
* **`genetic_queen(population, fitness)`:** Implements the core genetic algorithm loop.
* **`print_chromosome(chrom)`:** Prints a chromosome and its fitness value.
* **`print_board(board)`:** Displays the chessboard configuration.

Usage

1. Clone or download the repository.
2. Run the Python script. Example: `python nqueens_ga.py`
3. Enter the desired number of queens when prompted.
4. The script will generate an initial population, evolve it using the genetic algorithm, and display the final solution.

Dependencies

* Python 3
* Matplotlib (for visualization)

Genetic Algorithm

The genetic algorithm simulates an evolutionary process to find optimal solutions. In this case:

1. **Initialization:** Generates random potential solutions (chromosomes).
2. **Selection:** Chromosomes with higher fitness have a greater chance of being selected.
3. **Reproduction:** Selected chromosomes are combined to produce new potential solutions.
4. **Mutation:**  Small random mutations are introduced to maintain diversity.
5. **Repeat:** Steps 2-4 are repeated over generations until a solution is found.

Contributing

Feel free to contribute by suggesting improvements, reporting bugs, or experimenting with different genetic algorithm parameters.

License

This project is released under the MIT License.

