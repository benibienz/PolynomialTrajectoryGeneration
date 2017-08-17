# PolynomialTrajectoryGeneration
Polynomial Trajectory Generation incl. jerk minimizing trajectories and cost functions
Cloned from Udacity Self Driving Car Nanodegree

1.  ptg.py - The primary code for generating a polynomial trajectory for some constraints. This is also where weights are assigned to cost functions. Adjusting these weights (and possibly adding new cost functions), can have a big effect on vehicle behavior.
2.  cost_functions.py - This file contains many cost functions which are used in ptg.py when selecting the best trajectory. Some cost functions aren't yet implemented...
3.  evaluate_ptg.py - This file sets a start state, goal, and traffic conditions and runs the PTG code. Feel free to modify the goal, add traffic, etc... to test your vehicle's trajectory generation ability.
4.  constants.py - constants like speed limit, vehicle size, etc...
5.  helpers.py - helper functions used by other files.

## Getting Started
From the project's directory, run python evaluate_ptg.py. You should see a plot similar to the one below. This plot shows the s (x-axis) and d(y-axis) trajectories followed by a vehicle in traffic (red) and a self driving car (blue).

## Other Important Dependencies

python >= 3
