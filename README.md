# Genetic Algorithm
Generates A Desired String from Random Set of characters using Genetic Algorithm



Outline of the Algorithm
The following outline summarizes how the genetic algorithm works:

1.The algorithm begins by creating a random initial population.(in our case its the Set of strings)

2.The algorithm then creates a sequence of new populations. At each step, the algorithm uses the individuals in the current generation to create the next population. To create the new population, the algorithm performs the following steps:

3.Scores each member of the current population by computing its fitness value. These values are called the raw fitness scores.

4.Scales the raw fitness scores to convert them into a more usable range of values. These scaled values are called expectation values.

5.Selects members, called parents, based on their expectation.

6.Some of the individuals in the current population that have lower fitness are chosen as elite. These elite individuals are passed to the next population.

7.Produces children from the parents. Children are produced either by making random changes to a single parent—mutation—or by combining the vector entries of a pair of parents—crossover.

8.Replaces the current population with the children to form the next generation.

9.The algorithm stops when one of the stopping criteria is met. 

refer  "https://www.mathworks.com/help/gads/how-the-genetic-algorithm-works.html "  for more details.
