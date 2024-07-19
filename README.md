# TravellingSalesman

## The Travelling Salesman Problem

Given a list of cities and the distances between them, what is the shortest path to visiting each and returning to the origin city?

## Objective

I developed 2 basic and 2 enhanced Python algorithms to solve the Travelling Salesman Problem. The algorithms chosen were Basic Greedy Search and Greedy Best First Search.

## Contents

The repository contains 8 city files, detailing the distances between each city, varying in length from 12 to 535 cities. Alongside this are the 4 algorithms (2 basic and 2 enhanced), and the best tour found using Basic Greedy Search and Greedy Best First search for each city file respectively. A proforma detailing the enhancements made to each algorithm is also provided.

## Algorithms

### Basic Greedy Search

A greedy search algorithm follows the heuristic of always visiting the nearest unvisited city. This city is then added to the list of visited cities and its distance is added to the total distance of the path. The algorithm iterates through the greedy search path lengths for each possible starting node and returns the shortest as the best possible path.

### Greedy Best First Search

A greedy best first search algorithm follows the heuristic of visiting the neighbouring city with the lowest estimated greedy completion through it. The algorithm utilises a priority queue to gradually expand the search tree from the starting node, always considering the path with the lowest estimated cost, until a complete solution is found. The algorithm then iterates through all starting nodes and returns the best possible path.




