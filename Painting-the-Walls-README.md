# leet-day91

# Minimum Cost to Paint Walls

## Problem Description

You are given two arrays, `cost` and `time`, representing the cost and time taken to paint a series of walls. There are two painters:

1. A paid painter who takes a specific amount of cost and time for each wall.
2. A free painter who takes no cost but one unit of time for each wall. However, the free painter can only be used if the paid painter is occupied.

The goal is to determine the minimum cost required to paint all the walls.

## Solution

The provided C++ solution uses dynamic programming to solve the problem. The `dp` array is used to keep track of the minimum cost to paint the walls. The solution iterates through the walls and updates the `dp` array, considering both paid and free painters.

## How to Use

To use this solution, you can include the code in your C++ project. The `paintWalls` function takes two vectors, `cost` and `time`, and returns the minimum cost to paint all the walls.

Example usage:

```cpp
vector<int> cost = {1, 2, 3, 2};
vector<int> time = {1, 2, 3, 2};

Solution solution;
int minCost = solution.paintWalls(cost, time);
cout << "Minimum cost: " << minCost << endl;
```

Ensure that you have proper input validation and include the necessary header files.

