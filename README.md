# SC4003 Intelligent Agents Assignment 1: Agent Decision Making

## Project Overview
This assignment solves a stochastic gridworld using **Value Iteration** and **Policy Iteration**, then extends the analysis to more complex mazes.

<img width="558" height="581" alt="maze_environment" src="https://github.com/user-attachments/assets/68e179e2-7927-4d7f-998b-6cd3389a3a43" />

### Environment
- Actions: Up, Down, Left, Right
- Transition Model: 0.8 intended, 0.1 each perpendicular direction
- Rewards for Each State:
  - White = -0.05
  - Green = +1
  - Brown = -1
- No terminal states
- Discount Factor: 0.99

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
