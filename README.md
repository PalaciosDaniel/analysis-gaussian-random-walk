# Gaussian Random Walk Simulation

This project explores the statistical properties of a **Gaussian random walk**, a foundational model in quantitative finance and stochastic processes. The goal is to simulate multiple random walk paths, analyze their returns, and compare empirical observations with theoretical expectations.

## Project Goals

- Simulate Gaussian random walks and visualize sample paths.
- Analyze the distribution of returns and final prices.
- Examine volatility scaling via the Hurst exponent.
- Study tail behavior and extreme events.
- Assess autocorrelation in returns and squared returns.
- Understand the limitations of Gaussian random walks compared to real financial assets.

## Key Findings

- **Returns are normally distributed**, while prices are log-normally distributed due to exponentiation.
- **Volatility scales with the square root of time**, and the Hurst exponent is close to 0.5 for both returns and squared returns.
- **Tails decay exponentially**, confirming no heavy-tail behavior.
- **Autocorrelation is negligible**, indicating no temporal memory or volatility clustering.
- Gaussian random walks capture basic statistical properties but **do not reproduce features observed in real markets** such as heavy tails, long-term dependence, or volatility clustering.



