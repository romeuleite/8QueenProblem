# The 8 Queen Problem

The 8 queen problem is a classic, well-known problem in artificial intelligence and combinatorial optimization.

## Objective

The goal is to place eight queens on an 8x8 chessboard so that no two queens threaten or attack each other. To prevent the queens from attacking one another, no two queens should be in the same row, column, or diagonal.

## Approach

One approach to solving this problem is using a genetic algorithm (GA). A genetic algorithm is an informed search heuristic greatly inspired by the biological principles of natural selection and genetics.

It iteratively enhances a population of potential solutions by simulating the natural evolution process, which includes mutation, crossover, and selection. The process continues until a satisfactory solution or the maximum number of generations is reached.

### Fitness Evaluation

Calculate each potential solution's fitness. The number of non-attacking pairs in the 8-Queens puzzle determines its fitness function.

### Selection

Select parents from the current population to create the next generation.

### Crossover

Perform crossover between pairs of parents to create new offspring. Crossover involves exchanging genetic information to create a child solution.

### Mutation

Bring minor changes or mutations to the existing offspring solutions to maintain diversity and explore the search space. In this problem, mutation can involve swapping two positions in a board state.
