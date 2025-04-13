# Portfolio Optimization in Continuous Time

**Short Description:**  
This project explores optimal investment strategies using Merton's continuous-time portfolio theory and Bayesian enhancements, applied to Dow Jones Industrial Average (DJIA) stocks and G10 currency triplets. It combines quantitative modeling, real market data, and statistical analysis to assess profitability and hedging effectiveness.

---

### Conducted at  
**Frankfurt School of Finance and Management**  
Fall 2024 — Supervised by Prof. Jan Vecer

---
This project was created as part of an academic course at Frankfurt School of Finance and Management. It is shared here for educational and portfolio purposes only.

## Project Structure

This repository contains a single Jupyter notebook:
- `Portfolio_optimization.ipynb`: A complete, self-contained Python notebook that implements all parts of the project using real financial and FX data.

---

## Project Description

The project is divided into **two parts**:

### Part 1: Merton's Optimal Portfolio on DJIA Stocks

1. **Data Acquisition**  
   Historical stock price data for Dow Jones components starting from **January 1, 2010**.

2. **Return and Volatility Analysis**  
   - Compute simple returns and estimate volatility for each stock.
   - Visualize time series and summary statistics.

3. **Optimal Portfolio Construction**  
   - Implement **Merton’s optimal portfolio** based on user-defined drifts.
   - Compare it with **Markowitz’s mean-variance portfolio** and a fully risky asset.

4. **Performance Metrics**  
   - Calculate and visualize **Sharpe Ratios** and **Maximum Relative Drawdowns**.
   - Summarize results in a DataFrame.

5. **Hedging Validation**  
   - Check hedging effectiveness of the Merton strategy.

6. **Bayesian Merton Portfolio**  
   - Introduce drift uncertainty modeled via a **Bayesian approach**.
   - Compare Bayesian Merton vs classical Merton.

---

### Part 2: Currency Triplet Strategy in the G10 Market

1. **Mean-Reverting Return Assumption**  
   - Apply a scaled covariance model to identify opportunities in currency triplets (using EUR as a base).

2. **Portfolio Construction & Hedging**  
   - Compute optimal weights using subjective vs objective covariance matrices.
   - Use the provided `weights` and `MY` functions.

3. **Performance Analysis**  
   - Evaluate the portfolio across 36 EUR-based triplets.
   - Visualize returns and compare benchmarks (EUR, two foreign currencies, index).

4. **Hedging and Replication**  
   - Replicate portfolio prices using computed hedges.
   - Compare against theoretical values visually.

---

## Technologies Used

- **Python** (Jupyter Notebook)
- `pandas`, `numpy`, `matplotlib`, `yfinance`
- Quantitative Finance Methods
- Bayesian Modeling, Stochastic Processes

---

## Results

- In-depth performance comparisons between Merton, Markowitz, and fully risky portfolios
- Effective hedge verification
- Bayesian enhancement of Merton’s strategy
- Empirical results on G10 currency triplets

