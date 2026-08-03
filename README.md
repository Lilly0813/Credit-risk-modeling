# Credit Risk Basket CDS Pricing

A quantitative credit risk modeling project implementing Basket CDS pricing using Gaussian Copula and Monte Carlo simulation in Python.

## Project Overview

This project develops a Basket CDS pricing framework using Gaussian Copula and Monte Carlo simulation techniques.

The model estimates default correlation among multiple reference entities and calculates fair spreads for k-th-to-default credit derivatives.

## Objectives

• Estimate default probabilities

• Build credit correlation matrices

• Implement Gaussian Copula simulation

• Price 1st-to-Default through 5th-to-Default Basket CDS

• Perform sensitivity analysis

• Evaluate model risk under different correlation assumptions

## Methodology

The project follows a step-by-step quantitative credit risk modeling workflow:

1. Collect historical market data
2. Estimate default probabilities
3. Estimate correlation matrices
4. Generate correlated default scenarios using a Gaussian Copula
5. Price Basket CDS contracts using Monte Carlo simulation
6. Validate the model through sensitivity analysis

## Skills Demonstrated

- Credit Risk Modeling
- Basket CDS Pricing
- Gaussian Copula
- Monte Carlo Simulation
- Correlation Estimation
- Default Probability Modeling
- Model Validation
- Sensitivity Analysis
- Python (NumPy, Pandas, SciPy, Matplotlib)

## Future Improvements

Future enhancements may include:

- Market CDS curve calibration
- t-Copula implementation
- Stochastic recovery rates
- Discounted premium and protection leg valuation
- Historical backtesting

## Requirements

- Python 3.11+
- NumPy
- Pandas
- SciPy
- Matplotlib
- yfinance
- Jupyter Notebook

## Project Structure

Data/
│
├── bank_prices.csv
│
Notebooks/
│
├── 01_data_collection.ipynb
├── 02_default_probability_model.ipynb
├── 03_correlation_estimation.ipynb
├── 04_gaussian_copula.ipynb
├── 05_basket_cds_pricing.ipynb
└── 06_model_validation_and_sensitivity_analysis.ipynb

## Conclusion

This project demonstrates the implementation of a quantitative credit risk pricing framework using Gaussian Copula and Monte Carlo simulation.

It is intended as both an academic CQF project and a practical portfolio project showcasing quantitative finance and credit risk modeling skills.

