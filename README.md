# simulated-annealing

SA is a stochastic global optimization algorithm. As many other randomized algorithms, SA appears to be surprisingly simple, yet efficient at achieving its task (given conditions). The name and inspiration for the algorithm come from metallurgy, where controlled heating and cooling of the material allows it to form larger crystalline structure and improve properties. A popular description of the method can be found on Wikipedia page.

## Task 1. Iris Dataset
A feedforward neural network can utilize simulated annealing to learn a classifier for the Iris data set.
Define a Feed Forward NN (using your favorite framework)
Fit the neural network using simulated annealing as an optimization method (as sampling could be slow in high dimensional 4. 4. spaces, use fewer hidden layers or neurons)

### Findings

## Task2. Combinatorial optimization
Due to the nature of this optimization approach, it does not require the function to be differentiable. This allows to apply this method to optimize combinatorial problems.

Consider the traveling salesman problem
 * Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city once and returns to the origin city?

Find the optimal traveling salesman path using SA for 30 most populated cities

### Findings

We have applied simulated annealing to find the optimal path for traveling salesman problem of 30 russian cities. Below are the results for three defferent values of the annealing rate.

The slow cooling rate gives optimal result and converges at a rather late time, it took few thousands of steps to reach an optimal path.

For an annealing rate of middle value the convergence seems to be fast. Refer to figure

It took 50+ steps for to converge to fast cooling rate.
