# Evolutionary Algorithm Parameter Optimization

## Overview
This project explores the effects of various parameters on the performance of evolutionary algorithms. The parameters under consideration include mutation rate, selection pressure, and population size. These parameters are crucial in determining the convergence speed, solution quality, and robustness of the algorithm. By experimenting with different settings for these parameters, the project aims to identify optimal configurations that enhance the effectiveness and efficiency of the algorithm.

The choice of these parameters in evolutionary algorithms is crucial for achieving optimal performance. Parameters such as mutation rate, selection pressure, and population size directly influence the search process and can significantly affect the convergence speed, solution quality, and robustness of the algorithm. Inappropriate parameter settings can lead to premature convergence, stagnation, or excessive exploration, reducing the effectiveness and efficiency of the algorithm. For example, the mutation rate controls the frequency and intensity of genetic changes in the population, affecting the exploration of the search space. Similarly, the selection pressure determines the intensity of the competition between individuals and affects the exploitation of promising solutions. A high selection pressure may lead to premature convergence and local optima trapping, while a low selection pressure may cause insufficient exploitation and slow convergence. Moreover, the population size determines the diversity and density of the population, which directly affects the exploration and exploitation trade-off. A small population size may lead to insufficient diversity and exploration, while a large population size may cause excessive computation and redundancy. 

2. The three parameter values and the best performance are listed in the output for each selection algorithm. The metric used to report the best performance out of the three settings is the solution quailty. 

## Purpose
The purpose of this project is to investigate the influence of key parameters on evolutionary algorithms:
- **Mutation Rate:** Controls the frequency and intensity of genetic changes in the population, impacting the exploration of the search space.
- **Selection Pressure:** Determines the competition intensity between individuals, affecting the exploitation of promising solutions.
  - High selection pressure may lead to premature convergence and local optima trapping.
  - Low selection pressure may result in insufficient exploitation and slow convergence.
- **Population Size:** Affects the diversity and density of the population, influencing the exploration-exploitation trade-off.
  - Small population size may lead to insufficient diversity and exploration.
  - Large population size may cause excessive computation and redundancy.

## Project Description
Evolutionary algorithms are a class of optimization algorithms inspired by natural selection and genetics. This project includes implementing and testing different selection algorithms and measuring their performance based on solution quality.

### Selection Algorithms
1. **Proportional Selection**
2. **Truncation Selection**
3. **Deterministic Tournament Selection**
4. **Linear Ranking Selection**
5. **Stochastic Binary Tournament Selection**

### Key Components
- **Shekel's Foxholes Function:** The optimization problem used to evaluate the performance of the algorithms.
- **Initialization and Fitness Evaluation:** Functions to initialize the population and evaluate their fitness.
- **Selection Methods:** Different selection mechanisms implemented to select parents for the next generation.
- **Crossover and Mutation:** Genetic operators used to generate offspring.
- **Main Function:** Orchestrates the evolutionary process by iterating through generations, applying selection, crossover, and mutation, and evaluating fitness.
