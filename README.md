# Black-Scholes Model Implementation
This repository provides a Python implementation of the Black-Scholes option pricing model, along with practical trading examples and visualizations. The Jupyter notebook demonstrates how to calculate theoretical option prices, simulate stock price paths, and evaluate trading strategies based on model-market discrepancies.


**Key Features**

Black-Scholes Formula Implementation: Compute European call option prices using the closed-form Black-Scholes solution.

Dynamic Stock Price Simulation: Generate Geometric Brownian Motion (GBM) paths to model underlying asset behavior.

Trading Strategy Analysis: Identify potential arbitrage opportunities by comparing model prices with market quotes.

Monte Carlo Profit/Loss Simulation: Estimate expected trading outcomes using 100,000 simulated price paths.

Visualizations: Plot stock price trajectories and option payoff diagrams.

**Dependencies**

Python 3.7+

numpy

scipy

matplotlib

qfin (install via pip install qfin)

**Usage**

Clone repository

Install dependencies

Run Black_Scholes_Trading_Model.ipynb

Modify parameters to test different scenarios


This implementation demonstrates both theoretical pricing and practical trading applications of the Black-Scholes model. The included simulations help evaluate statistical arbitrage opportunities while emphasizing the model's assumptions about market dynamics.
