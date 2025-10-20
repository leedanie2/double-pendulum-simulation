# Double Pendulum Simulation & Analysis

**Author:** Daniel Lee  
**Course:** PHY-234 Mechanics Lab — Grinnell College  
**Tech:** Python, NumPy, SciPy (`solve_ivp`), Matplotlib, Jupyter Notebook

## Overview
This project models a double pendulum using Lagrangian mechanics and numerical integration. It produces time-series data, state-space plots, Poincaré sections, and animations to illustrate chaotic and periodic dynamics under different initial conditions.

## What I did
- Derived equations of motion from Lagrangian mechanics (see `double_pendulum.ipynb`).
- Implemented a numerical integrator with SciPy's `solve_ivp` to generate time-series data for angular positions and velocities.
- Ran parameter sweeps to explore regimes (chaotic vs periodic), and validated results using limiting cases.
- Created visual outputs: time-series plots, state-space diagrams, Poincaré sections, and an animation of the pendulum motion.
- Documented methodology and results in `report.pdf`.

## Files
- `double_pendulum.ipynb` — Jupyter notebook with derivation, code, and visualizations.
- `report.pdf` — Final lab report summarizing findings.
- `images/` — Plots and animation GIFs.
- `requirements.txt` — Python package requirements.

## How to run (locally)
1. Clone the repo:
   ```bash
   git clone https://github.com/<username>/double-pendulum-simulation.git
   cd double-pendulum-simulation
