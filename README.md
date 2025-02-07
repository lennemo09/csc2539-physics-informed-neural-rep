# csc2539-physics-informed-neural-rep
Collection of my implementation of basics concepts from papers discussed in the course CSC2539: Physics-Informed Neural Representations for Visual Computing at the University of Toronto (Winter 2025).
--
## Table of Contents

| Week | Topic | Directory |
| --- | --- | --- |
| 1 | [Physics-Informed Neural Networks (PINNs)](#week-1-physics-informed-neural-networks-pinns) | [Link](/wk1-pinn) |

## Week 1: Physics-Informed Neural Networks (PINNs)

### Introduction to PDEs, Nonlinear PDEs, and Finite Difference Numerical Solvers
In this notebook, we introduce partial differential equations (PDEs), discuss the difference between linear and nonlinear PDEs, and learn about finite difference methods for numerically solving PDEs. We implement and visualize solutions for two examples:
- The Heat Equation (a linear PDE).
- Burgers' Equation (a canonical nonlinear PDE), a fundamental nonlinear partial differential equation used in fluid mechanics and nonlinear wave propagation.

You can find the notebook [here](/wk1-pinn/pde.ipynb).

### PINN for Burger's Equation
This notebook focuses on the Burger's equation introduced in the previous notebook. This time, we uses PINN to generate the solution, which is visualized and compared against the finite difference solver. 

You can find the notebook [here](/wk1-pinn/pinn.ipynb).

![Burger's Equation Solution Comparison](/wk1-pinn/burgers_solution_evolution.gif)


### PINN for Damped Spring Simulation
In this notebook, we simulate a damped spring system using a traditional numerical method and visualize its time evolution. We then use a Physics-Informed Neural Network (PINN) to reconstruct the damped spring simulation.

You can find the notebook [here](/wk1-pinn/pinn_spring.ipynb).

![Damped Spring Simulation](/wk1-pinn/damped_spring_vertical_animation.gif)