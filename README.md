# Search-algorithm-aiml-mdm

# Search Algorithm Performance Evaluation

## TY B.Tech. Artificial Intelligence and Machine Learning – Practical

### Practical Title

**Evaluate the performance of various algorithms (Uninformed, Informed, Local Search and Constraint Satisfaction) of problem solving through Search.**

---

## 1. Aim

To implement and evaluate different Artificial Intelligence search algorithms and compare their performance based on:

- Path found
- Total path cost
- Number of nodes explored
- Execution time

The practical implements:

1. Breadth First Search (BFS)
2. Depth First Search (DFS)
3. Greedy Best-First Search
4. A* Search
5. Hill Climbing
6. N-Queens using Backtracking

---

## 2. Problem Statement

Implement various search algorithms used in Artificial Intelligence for solving problems through search.

The algorithms are categorized as:

| Category | Algorithm |
|---|---|
| Uninformed Search | Breadth First Search |
| Uninformed Search | Depth First Search |
| Informed Search | Greedy Best-First Search |
| Informed Search | A* Search |
| Local Search | Hill Climbing |
| Constraint Satisfaction | N-Queens using Backtracking |

The algorithms are evaluated using a city-map problem where the objective is to find a path from **Pune to Mumbai**.

---

## 3. Objectives

- To understand different search strategies used in Artificial Intelligence.
- To implement Uninformed Search algorithms.
- To implement Informed Search algorithms using heuristic functions.
- To implement Local Search using Hill Climbing.
- To solve a Constraint Satisfaction Problem using Backtracking.
- To compare search algorithms based on nodes explored, path cost, and execution time.

---

## 4. Algorithms Implemented

### 4.1 Breadth First Search (BFS)

BFS explores the search space level by level.

It uses a **Queue (FIFO)** data structure.

**Characteristics:**

- Uninformed search
- Complete
- Suitable for finding the shortest path in terms of number of edges
- Requires more memory for large search spaces

---

### 4.2 Depth First Search (DFS)

DFS explores one branch as deeply as possible before backtracking.

It uses a **Stack (LIFO)** data structure.

**Characteristics:**

- Uninformed search
- Memory efficient compared to BFS
- Does not guarantee an optimal path
- Can explore a deep branch before finding a better solution

---

### 4.3 Greedy Best-First Search

Greedy Best-First Search uses a heuristic function to select the node that appears closest to the goal.

The evaluation function is:

```text
f(n) = h👎
