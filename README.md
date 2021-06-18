# SJJP-Optimization

Job Shop Scheduling Problem (JSSP) is a scheduling problem in which we need to assign n jobs with a number of operations to be scheduled on the m machines. Each operation of a job has to be scheduled on a machine without overlapping with any other operations. There are various approaches to optimize the JSSP. In this project various approaches have been implemented and compared to find the most optimal one.

The first approach used to solve the JSSP is the traditional one. This approach provides a set of bench mark for JSSP. The traditional approach covers the methods like mathematical programming, linear programming, integer programming, branch and bound method, surrogate duality method, dynamic programming etc. The approach that we have used is of dynamic progrming.

The second method used is Particle Swarm Optimization (PSO) which is a hybrid algorithm and provides a metaheuristic approach to solve the JSSP. The improved version of PSO i.e. Improved Particle Swarm Optimization (IPSO) has been implemented with TABU search (TS) to find the optimal solutions scattered over the huge search space. Besides a real integer encoding and decoding approach has been used to map the continuous space of the PSO to the discrete solutions of the JSSP.
The third used approach is an Ant Colony Optimization (ACO) based on the intelligence of the of the PCO. ACO-PSO hybrid algorithm uses the PSO to optimize parameters and to provide the self-adaptation to the ACO.

The last approach is of the Genetic Algorithms (GA) which is a very popular heuristic approach. To solve the JSSP using the GA the initial population is first created and then different genetic operations like crossover, mutation, repair and selection are applied on the generated populations and best among them are selected on the basis of the value of the fitness function. When the termination condition met the best among the population served as the solution to the JSSP. Simulations for these approaches have be run on the Tailliard series and the contrast is draw among the different opted approaches on the basis of the makespan value, execution time, best- relative error and the average-relative error.

### Watch Simulation of Hybrid Particle Swarm Optimization for JSSP
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/2knod3NxjaY/0.jpg)](https://www.youtube.com/watch?v=2knod3NxjaY)
