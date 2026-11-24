# India Electricity Time Series Analysis (2015–2025)

## Project Overview

This project investigates the determinants of regional electricity shortages in India between 2015 and 2025. It examines the relationship between coal availability, distribution inefficiencies, generation performance, renewable energy penetration, demand conditions and electricity supply deficits.

The study uses monthly data covering 36 Indian states and union territories, comprising 4,752 observations across 132 months.

## Project Objectives

- Identify trend, seasonal and irregular patterns in electricity shortages.
- Examine stationarity and short-run time series dynamics.
- Develop forecasting models to analyse electricity shortage patterns.
- Investigate volatility in energy market returns.
- Establish the long-run relationship between coal availability and electricity shortages.
- Translate statistical findings into policy implications for India's energy sector.

## Dataset Overview

The analysis uses eight variables:

- Shortage Percentage
- Coal Stock Days
- ATC Loss Percentage
- Plant Load Factor
- Renewable Energy Share
- Nifty Energy Returns
- Average Temperature Index
- Import Dependency

**Dataset Coverage:** January 2015 – December 2025  
**Geographical Coverage:** 36 Indian States and Union Territories  
**Observations:** 4,752

## Tools & Technologies

- R Programming
- Time Series Analysis
- ARIMA Modelling
- ARCH and GARCH Models
- Statistical Hypothesis Testing
- Data Visualisation

## Methodology

### 1. Time Series Decomposition
Applied classical additive and multiplicative decomposition, along with STL decomposition, to identify trend, seasonal and irregular components.

### 2. Stationarity Testing
Used three statistical tests:
- Augmented Dickey-Fuller (ADF)
- KPSS Test
- Phillips-Perron (PP) Test

### 3. AR, MA and ARIMA Modelling
Developed autoregressive, moving average and ARIMA models to capture short-run dynamics and generate forecasts.

### 4. Volatility Modelling
Conducted ARCH-LM testing to identify volatility clustering and applied ARCH(1) and GARCH(1,1) models to examine conditional volatility in energy market returns.

### 5. Cointegration and Error Correction Model
Applied the Engle-Granger approach to investigate the long-run relationship between coal stock availability and electricity shortages, followed by an Error Correction Model (ECM).

## Key Findings

- Coal stock days demonstrated a strong negative relationship with electricity shortages.
- The long-run regression reported an R² of 0.944.
- The ECM adjustment coefficient was -0.941, indicating rapid correction of long-run disequilibrium.
- The selected ARIMA model was ARIMA(0,1,0)(0,0,2)[12], with a MAPE of 8.07%.
- ARCH-LM testing confirmed significant volatility clustering in energy market returns.

## Project Deliverables

- R-based analysis and statistical modelling in HTML format.
- Research report documenting the methodology, results and interpretations.

