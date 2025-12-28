# Cambodia Inflation Rate Forecasting

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Dataset](https://img.shields.io/badge/Datasets-5-yellowgreen)](#data-sources)

Forecasting Cambodia's inflation rate using multiple statistical models to provide actionable insights for economic planning and strategy.

## Project Overview

Understanding inflation trends is critical for policymakers, businesses, and investors. This project leverages historical data and statistical modeling to:

* Analyze historical inflation patterns
* Understand the influence of exchange rates, trade, and fuel prices
* Forecast future inflation trends for informed decision-making

The project compares multiple time series models to improve predictive accuracy and identify key drivers of economic change.

---

## Data Sources

| Dataset                          | Description                         |
| -------------------------------- | ----------------------------------- |
| `cam-inflation-2005-2025.csv`    | Historical Cambodia inflation rates |
| `khr-usd-exchange-2003-2023.csv` | KHR/USD exchange rate trends        |
| `export-2015-2025.csv`           | Cambodia export data                |
| `import-2015-2025.csv`           | Cambodia import data                |
| `fuel-price-2023-2025.csv`       | Fuel price trends                   |


## Models and Methodology

| Model                   | Description                                                             |
| ----------------------- | ----------------------------------------------------------------------- |
| **AR (AutoRegressive)** | Predicts future values using past inflation data                        |
| **MA (Moving Average)** | Models short-term dependencies based on past errors                     |
| **ARMA**                | Combines AR and MA components for better accuracy                       |
| **ARIMA**               | Handles non-stationary data with differencing plus AR and MA components |

---
