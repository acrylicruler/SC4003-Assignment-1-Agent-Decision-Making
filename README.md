# SC4003 Intelligent Agents Assignment 1: Agent Decision Making

## Project Overview
This assignment solves a stochastic gridworld using **Value Iteration** and **Policy Iteration**, then extends the analysis to more complex mazes.

### Environment
- Actions: Up, Down, Left, Right
- Transition model: 0.8 intended, 0.1 each perpendicular direction
- Rewards:
  - white = -0.05
  - green = +1
  - brown = -1
- No terminal states
- Discount factor: 0.99

## Part 1
- Solve the given maze with:
  - Value Iteration
  - Policy Iteration
- Display:
  - Optimal policy
  - Utilities of all non-wall states
  - Convergence plots

## Part 2
- Test more complicated maze environments
- Compare the effects of:
  - Wall density
  - Grid size
  - Overall maze complexity
- Evaluate convergence behaviour and runtime


## Repository Structure
- `SC4003_Assignment1_Question.pdf` — Assignment Brief
- `SC4003_Assignment1_ValueIteration.ipynb` — Part 1 Value Iteration
- `SC4003_Assignment1_PolicyIteration.ipynb` — Part 1 Policy Iteration
- `SC4003_Assignment1_Part2.ipynb` — Part 2 Maze Complexity Experiments
- `SC4003_Assignment1_Report.pdf` — Report

## Author
Sally Ngui Yu Ying
