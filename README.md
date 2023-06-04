# Option-Pricing-Risk-Analysis-Stochastic-Models
This repository contains a comprehensive project on option pricing and risk analysis using stochastic models in quantitative research and analysis.

## Project Overview
The goal of this project is to develop a rough framework for option pricing and risk analysis by implementing and calibrating stochastic models. The project includes data preprocessing, model selection, parameter estimation, option pricing, risk analysis, and sensitivity analysis.

## Project Structure
This project is organized as follows:

- `data/`: Contains the historical financial market data used for this project.
- `preprocessing/`: Includes scripts for data cleaning, alignment, and calculating implied volatility.
- `model/`: Contains the implementation of stochastic models including the Black-Scholes-Merton and Heston Models.
- `pricing/`: Includes scripts for option pricing based on the selected stochastic models and estimated parameters.
- `risk_analysis/`: Contains scripts for conducting risk analysis using Monte Carlo simulation
- `sensitivity_analysis/`: Includes scripts for performing sensitivity analysis on model parameters and market conditions.
- `results/`: Stores the generated outputs, including option prices, risk metrics, and visualizations.
- `docs/` : Contains the project documentation, including the report summarizing the project objectives, methodologies, and findings.

## Dependencies
This project has the following dependencies:

- Python 3.6
- NumPy
- Pandas
- Matplotlib

## Summary

### Data Collection
Gather historical financial data related to options, including the underlying asset prices, option prices, and relevant market indicators.

### Data Preprocessing
Clean and preprocess the financial data, handling missing values, aligning data to a consistent time frame, and calculating additional metrics such as implied volatility.

### Stochastic Model Selection
Choose a suitable stochastic model such as the Black-Scholes-Merton model, Heston model, or a combination of models that incorporate stochastic volatility and jumps.

### Parameter Estimation
Utilize optimization techniques or maximum likelihood estimation to estimate the model parameters based on historical data, including volatility, drift, and jump intensity parameters.

### Option Pricing
Implement the chosen stochastic model to price options based on the estimated parameters and the underlying asset prices. Calculate option Greeks such as delta, gamma, theta, and vega.

### Risk Analysis
Conduct risk analysis by simulating potential scenarios using Monte Carlo simulation or other numerical methods. Generate a large number of possible future paths for the underlying asset prices and calculate corresponding option values and risk metrics.

### Model Calibration and Validation
Calibrate the stochastic model to match observed option prices and assess the model's accuracy and goodness-of-fit using statistical measures such as mean squared error or root mean squared error.

### Sensitivity Analysis
Perform sensitivity analysis to understand the impact of changing model parameters, market conditions, or implied volatility on option prices and risk metrics.

### Documentation and Presentation
Prepare a comprehensive report summarizing the project objectives, the selected stochastic models, the parameter estimation techniques, option pricing results, risk analysis findings, and sensitivity analysis. Include visualizations, model equations, and detailed explanations.

## License
This project is licensed under the [MIT License](LICENSE)

## Aknowledgements

