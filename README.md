# Monopoly MDP Simulation
Overview
This Jupyter Notebook provides a detailed simulation and analysis of the Monopoly board game, modeled as a Markov Decision Process (MDP). It utilizes various strategies to assess optimal gameplay tactics based on return on investment (ROI) thresholds.

*Goal*: The goal of this notebook is to provide a comprehensive simulation of Monopoly, allowing users to explore various strategic decisions and their outcomes in the game, using data-driven methods to optimize gameplay strategies.


### Markov Chain Analysis: 
Establishes the basic probabilistic transitions between Monopoly spaces, allowing for an analysis of game dynamics under simplified conditions.
### ROI-Based Strategy Simulation: 
Implements strategies where players decide to buy properties based on expected returns, simulating different approaches to property acquisition.
### Optimization of Strategies: 
Uses the Optim package to find the optimal ROI threshold that maximizes a player's chances of winning or maximizing end-game profit.
### Results Analysis: 
Compares win rates and average profits across different strategies, providing insights into effective Monopoly gameplay.
Usage
To run this notebook:

Ensure you have a Julia environment with required packages (Optim, DataFrames, Random).
Execute the cells sequentially to observe how different strategies perform under a simulated Monopoly game environment.
