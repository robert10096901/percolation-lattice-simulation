# Percolation Lattice Simulation

This repository contains a Jupyter Notebook that estimates percolation thresholds using lattice structures in both 2D and 3D.

## Contents

- `Percolation_threshold_estimate.ipynb`: Main notebook that includes two separate simulation blocks:
  1. **Standard Lattice Percolation** (supports both 2D and 3D structures)
  2. **Random Lattice Percolation**

## Description

The simulation uses Monte Carlo techniques to estimate percolation thresholds for lattices:

- The **first part** of the notebook simulates traditional lattice systems, where the connectivity is regular (either in 2D or 3D).
- The **second part** explores random lattice structures, where the connections are randomized.

Each part outputs percolation probability plots and threshold estimates based on varying system sizes.

## Requirements

Make sure to install the following Python packages before running the notebook:

```bash
pip install numpy matplotlib scipy
