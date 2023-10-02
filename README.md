

----------------------

Finally, the numeric result is compared to the analytic one and an animation of the behavior for different distance between tips is shown.

In order to run it you can open it with Google Colaboratory from GitHub or dowload and run it in your local machine usin Jupyter notebook.

# Catenary Simulation

This repository contains a Jupyter Notebook-based Python program that performs a simulation and numerical analysis of catenary curves, along with visualization and animations of the results. The script uses various numerical methods to calculate the shape of a catenary curve and compares it with the real function.

## Introduction

A catenary is the curve that a flexible cable assumes when uniformly loaded and suspended between two fixed points. This script aims to calculate and visualize the shape of a catenary curve under specific parameters, perform numerical integration using different methods, and animate the results.

## Features

- Calculation of catenary curve using numerical methods
- Numerical integration using Simpson's rule and Gaussian quadrature
- Visualization of catenary shape and comparisons with real functions
- Animated demonstrations of the calculation and interpolation processes

## Getting Started

1. Clone the repository to your local machine.
2. Open the Jupyter Notebook `catenary.ipynb` in your preferred Jupyter environment.

## Usage

1. Open the Jupyter Notebook and follow the instructions provided within.
2. The notebook utilizes the following methods:

    - **Steffensen's method** for finding roots.
    - **Simpson's integration method** for numerical integration.
    - **Method of Gaussian integration** for accurate integrations.
    - **Euler's method** for solving differential equations.
    - **Interpolation by cubic splines**, using the function CubicSpline from the Scipy library.

3. Run each cell sequentially.
4. The program will generate numeric results and compared them to the analytic ones.
5. The program will proceed to present an animation of the behavior of the catenary for different distances between the edges.


## Note

This program is intended for educational purposes and provides insights into gas behavior using different equations of state. The accuracy of results may vary based on the chosen equations and assumptions.

Remember to use a Jupyter environment to execute the notebook effectively.
