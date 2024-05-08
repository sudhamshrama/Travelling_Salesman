## Problem Solver for Traveling Salesmen

This project is a Python implementation of the Genetic Algorithm (GA) method for solving the Traveling Salesman Problem (TSP). In the classic optimization problem known as the "Traveling Salesman Problem," a salesperson has to determine the shortest path that visits each city exactly once and returns to the starting point.

## What is the issue with traveling salespeople?

In combinatorial optimization, one well-known NP-hard problem is the Traveling Salesman Problem (TSP). In its most basic form, it can be explained like this:

Determine the shortest path that visits each city precisely once and returns to the starting city, given a list of cities and the distances between each pair of cities.

The issue presents a computational challenge because the number of possible pathways becomes exponentially. Because of the factorial expansion of viable routes with the number of cities, the problem is computationally hard and cannot be solved optimally for big instances.

## Concerning the Algorithm

Inspired by natural selection, the Genetic Algorithm (GA) is a widely used heuristic approach to solve optimization issues. Within the framework of the TSP, the GA functions through generational evolution of a population of candidate solutions (tours), each of which represents a possible path. In order to generate fresh generations of tours and increase the overall fitness (shortness) of the routes, the algorithm iteratively uses selection, crossover, and mutation operators.
