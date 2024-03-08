# Analysis of Household Credit Liabilities in Canada

This repository contains Python code for analyzing household credit liabilities in Canada using time series analysis techniques. The code retrieves and processes data from a CSV file named `kanada.csv`, then performs various analyses and visualizations.

## Code Overview

The Python script performs the following tasks:

1. Reads the data from the CSV file `kanada.csv` and preprocesses it.
2. Generates visualizations to analyze trends and patterns in non-mortgage loans:
   - Distribution of non-mortgage loans taken out on average.
   - Box plot showing the distribution of non-mortgage loans held by year.
   - Box plot showing the total amount of non-mortgage credit per month.
   - Line chart showing the trend of non-mortgage loans by year.
   - Plotting each time series component
3. Calculates and displays statistical information:
   - Mean value and standard deviation of non-mortgage loans by year.
4. Applies time series forecasting models:
   - Holt Winters' model for trend estimation.
   - SARIMA model for forecasting.

## Dependencies
- pandas
- matplotlib
- seaborn
- statsmodels
- pmdarima

