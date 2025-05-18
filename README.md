# Percolation threshold Simulation

This repository contains a Jupyter Notebook for estimating percolation thresholds in lattice-based systems using both regular and random structures in two and three dimensions.

## Contents

- `Percolation_threshold_estimate.ipynb`: A unified notebook comprising two simulation modules:
  1. Standard lattice percolation (2D and 3D)
  2. Random lattice percolation based on spatial proximity

## Description

This notebook implements Monte Carlo simulations to determine the percolation threshold, defined as the critical occupation probability at which a system transitions from a non-percolating to a percolating phase.

- In the **first module**, the simulation is based on regular 2D and 3D grid lattices with uniform connectivity. A breadth-first search (BFS) algorithm is used to detect spanning clusters.
- In the **second module**, the system is modeled as a random geometric network. Nodes are placed randomly in space, and connectivity is defined by a threshold distance. Percolation is assessed through randomly disabling nodes and analyzing the resulting network.

Both modules generate percolation probability curves and identify the threshold value via interpolation.

## Requirements

To run the notebook, install the following Python packages:

```bash
pip install numpy matplotlib scipy numba ipywidgets
