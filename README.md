# Numeric Computation for Financial Modeling

## Preface

This repository stores my solutions to computational problems in financial modelings

## Languages and technologies used

Python 3.10 (Numpy, Pandas, Scipy, Seaborn, Matplotlib), Jupyter Notebook

## Topics

The repository contains four folders: A1~A4.

Each folder covers the following topics:

### A1

* Binomial Lattice
    - Properties of Binomial Lattice
* Risk Neutral property
    - Risk neutral probability q*
* Fair value of european options
* Properties of standard Wiener Process (standard Brownian Motion)
    - Ito's Lemma

Non-programming questions; only hand-written answers

### A2

* Simulating drifting Binomial Lattice
    - Convergence rate of Binomial Lattice method
* Binomial Lattice with underlying with dividends (European Options)
    - Interpolation between missing underlying (stock) prices
* Monte Carlo simulation for European Options
    - Down-and-out call option
    - Time discretization error of MC simulation

### A3

* Numerical schemes for SDEs (Stochastic Differential Equations)
    - Euler-Maruyama method
    - Milstein Method
* Numerical schemes for correlated SDEs
    - Cholesky matrix and decomposition
* Delta hedging from a Binomial Lattice
    - European Butterfly Option
    - Interpolation between underlying (stock) prices
    - VaR (Value at Risk), cVaR (cumulative Value at Risk), and P&L (Profit and Loss) calculation from MC (monte carlo) simulation
* Trading simulation using monte carlo simulation
    - Use option value from Black-Scholes equation
    - Set various rebalancing strategy and evaluate the possibility of an arbitrage
* Jump Diffusion model
    - Double exponential jump process (probability distribution function is doubly exponential)
    - Add random jump process in the simulation
    - Compare observed implied volatility

### A4

* Finite Difference Method (FDM)
    - Apply fully-implicit, Crank-Nicolson, and CN-Rannacher method
    - Use sparse matrix to facilitate calculation (Scipy)
    - Convergence rate between the each method (linear / quadratic)
    - Plot graphs for delta and gamma of options (Are the gamma graph smooth?)
* FDM for American options, with variable timestepping
    - Apply fully-implicit, Crank-Nicolson, and CN-Rannacher method with variable timestepping
    - Is it never optimal to exercise early for American call options?
    - Plots of delta and gamma
* Model Calibration
    - Find implied volatility that explains the option price
    - Using simple feed forward neural network as the local volatility function (LVF)
    - Non-linear least square method using Jacobian Matrix, Levenberg-Marquardt method
    - Verify the model using 3d plot
* Optimal static hedging
    - Least squares optimization problems with conditions
    - Monte Carlo simulation to derive conditions
    - Lagrangian multipliers with Karush–Kuhn–Tucker (KKT) conditions
* cVaR and Convexity
    - Convexity test
    - cVaR optimization problem
