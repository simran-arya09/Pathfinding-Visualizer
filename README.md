# Pathfinding Visualizer

An interactive React application that visualizes how pathfinding algorithms search a grid to find a route between a start and end node. Built as a guided learning project to study how classic graph-search algorithms behave visually, step by step.

## What It Does

- Renders an interactive grid where users can set a start node, an end node, and walls/obstacles
- Visualizes the search process of different pathfinding algorithms in real time
- Lets users compare how each algorithm explores the grid differently

## Algorithms Covered

*(Confirm this list against your actual code before publishing — update to match what's really implemented)*

- Dijkstra's Algorithm (weighted, guarantees shortest path)
- A* Search (weighted, heuristic-based)
- Depth-First Search (unweighted)
- Breadth-First Search (unweighted)

## Tech Stack

- React (Create React App)
- JavaScript
- CSS / HTML

## Running Locally

```bash
npm install
npm start
```

Then open `http://localhost:3000` in your browser.

## Background & Credits

This project was built while following a guided pathfinding visualizer tutorial originally created by [Clément Mihailescu](https://github.com/clementmihailescu/Pathfinding-Visualizer). It was completed as a hands-on way to understand how graph traversal and shortest-path algorithms work under the hood, beyond just reading about them.

## What I Learned

- How weighted vs. unweighted search algorithms differ in behavior and guarantees
- How to represent a grid as a graph and run traversal algorithms over it
- How to manage and visualize step-by-step algorithm state in a React application
