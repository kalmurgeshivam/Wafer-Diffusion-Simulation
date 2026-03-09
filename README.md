
# Wafer Diffusion Simulation

## Overview

This project simulates dopant diffusion in a semiconductor wafer using the **Finite Difference Method (FDM)**.
The simulation models how dopant concentration changes with depth and time during the thermal diffusion process used in semiconductor fabrication.

## Problem Statement

To model and simulate the diffusion of dopants in a semiconductor wafer and analyze how concentration varies with depth during the diffusion process.

## Method Used

The simulation uses the **Finite Difference Method** to numerically solve the diffusion equation:

∂C/∂t = D ∂²C/∂x²

Where:

* C = Dopant concentration
* D = Diffusion coefficient
* x = Depth in the wafer
* t = Time

## Implementation

The simulation is implemented in **Python** using numerical computation techniques.

Key steps:

1. Define wafer depth and diffusion parameters.
2. Initialize dopant concentration profile.
3. Apply the finite difference approximation.
4. Update concentration values iteratively over time.
5. Plot the concentration vs depth profile.

## Tools Used

* Python
* NumPy
* Matplotlib

## Output Result

The simulation generates a concentration profile showing how dopant concentration varies with wafer depth.

Example output:

(Add your simulation graph screenshot here)

## Files in Repository

* `wafer_diffusion_simulation.py` – Python code for the simulation
* `Output Result.pdf` – Simulation result output
* `PROBLEM STATEMENT.pdf` – Problem description

## Applications

This simulation is useful for understanding semiconductor fabrication processes such as:

* Thermal diffusion
* Doping profile analysis
* Semiconductor device fabrication

