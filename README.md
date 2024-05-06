# Global Equity Market Volatility Spillovers

This repository contains the code and data for an empirical study on volatility dynamics and spillover effects across major global equity markets. The research analyzes volatility interdependencies and transmission mechanisms among developed and emerging stock markets, shedding light on financial market linkages in an increasingly interconnected global economy.

## Overview

The study examines daily returns data from nine equity market indices spanning the United States, Canada, Mexico, Saudi Arabia, United Arab Emirates, China, Hong Kong, Taiwan, and South Korea. It employs various statistical techniques, including tests for independence, stationarity, serial correlation, and normality, to investigate the stylized facts and properties of the return series.

To capture volatility dynamics, the analysis fits appropriate GARCH (Generalized Autoregressive Conditional Heteroskedasticity) models to the returns of each market index. The estimated conditional volatilities from these models are then used to analyze volatility transmission mechanisms across markets.

Key analyses include:

1. **GARCH-Models**: Estimating conditional volatilities using the symmetric GARCH models
2. **Variance-Covariance Matrix**: Exploring the co-movement and interdependencies among markets to assess the potential for volatility spillovers.
3. **Granger Causality Tests**: Examining the directional influence of volatility shocks across markets to uncover causal relationships and lead-lag effects.

## Repository Structure

- `data/`: Contains the processed data files for the equity market indices.
- `code/`: Includes R scripts for data preprocessing, model fitting, and analysis.
- `docs/`: Contains documentation, including the research paper and supplementary materials.

## Usage

1. Clone the repository: `git clone https://github.com/your-username/global-equity-volatility-spillovers.git`
2. Navigate to the project directory: `cd global-equity-volatility-spillovers`
3. Follow the instructions in the `docs/` directory to run the analysis scripts and reproduce the results.

## Dependencies

The analysis relies on the following R packages:

- `tseries`
- `fGarch`
- `ggplot2`
- `quantmod`
- ... (add other package dependencies)

Please ensure that these packages are installed before running the analysis scripts.

## Contributing

Contributions to this research project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgments

I would like to thank the data providers and the open-source community for their contributions to the tools and libraries used in this research.
