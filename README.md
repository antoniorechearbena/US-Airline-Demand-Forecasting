# US-Airline-Demand-Forecasting
# US Airline Demand Forecasting

Machine learning project focused on forecasting passenger traffic across US domestic airline routes using historical data from the Bureau of Transportation Statistics (BTS).

## Project Overview

Airlines must anticipate passenger traffic to plan flight frequencies, allocate aircraft, and efficiently manage available capacity.

This project aims to develop an end-to-end machine learning forecasting system capable of predicting monthly passenger traffic across US domestic airline routes.

The project will begin with historical passenger traffic forecasting and eventually explore how predictions can support airline capacity allocation decisions.

## Objectives

- Collect and process historical US domestic aviation data.
- Analyze passenger traffic trends, seasonal patterns, and route characteristics.
- Develop traditional forecasting baselines.
- Train and compare machine learning models, including Random Forest and XGBoost.
- Evaluate forecasting accuracy using chronological validation and backtesting.
- Build an interactive forecasting dashboard.
- Explore capacity optimization through scenario-based analysis.

## Data Source

**Bureau of Transportation Statistics (BTS)**

Primary dataset: T-100 Domestic Segment (All Carriers).

Historical period: 2018–2025 (initial scope).

The dataset provides information about passengers transported, seats available, departures performed, operating carriers, and airport pairs.

**Prediction target:** Monthly passengers carried on an airline-operated nonstop segment.

The model will estimate observed passenger traffic rather than unconstrained customer demand.

## Methodology

The project will follow these stages:

1. Data acquisition and validation
2. Data cleaning and route selection
3. Exploratory data analysis
4. Baseline forecasting
5. Feature engineering and machine learning
6. Model evaluation and backtesting
7. Forecasting application development
8. Capacity optimization scenarios

The initial forecasting horizon will be one month ahead, with the possibility of extending to longer horizons.

## Technology Stack

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook
- Streamlit

## Initial Modeling Strategy

The initial approach will train machine learning models using historical observations across multiple airline routes.

An individual route will subsequently be selected to demonstrate and analyze forecasting performance.

Candidate route: American Airlines, Dallas/Fort Worth (DFW) → Los Angeles (LAX), pending data validation.

## Project Status

**Current phase:** Project setup and data acquisition planning.

Model development and evaluation have not yet started.

## Future Development

Future extensions may include multi-month forecasting, passenger uncertainty estimates, aircraft capacity allocation, and flight-frequency optimization.

---

This project is an independent educational and portfolio project using publicly available US transportation data.
