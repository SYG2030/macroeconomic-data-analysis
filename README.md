# Macroeconomic Data Analysis

## Project Overview

This project analyzes macroeconomic indicators and their relationship with major stock market indices in Saudi Arabia and Russia.

The analysis focuses on identifying relationships between oil prices, interest rates, inflation, exchange rates, and stock market performance.

## Objectives

- Analyze trends in TASI and MOEX indices.
- Examine the relationship between oil prices and stock market indices.
- Investigate the relationship between macroeconomic indicators and market performance.
- Apply correlation analysis and multiple linear regression.
- Evaluate potential multicollinearity using Variance Inflation Factor (VIF).

## Dataset

The dataset contains 36 quarterly observations covering the period from **2015 Q1 to 2023 Q4**.

Variables include:

- Oil Price
- Saudi Arabia Interest Rate
- Russia Interest Rate
- Saudi Arabia Inflation
- Russia Inflation
- USD/SAR Exchange Rate
- USD/RUB Exchange Rate
- TASI Index
- MOEX Index

## Methods

The project uses:

- Python
- Pandas
- Matplotlib
- Seaborn
- Statsmodels
- Descriptive Statistics
- Correlation Analysis
- Ordinary Least Squares (OLS) Regression
- Variance Inflation Factor (VIF)

## Key Findings

### TASI Model

- The model explains approximately 16.5% of the variation in TASI (R² = 0.165).
- The overall regression model is not statistically significant at the 5% level (F-test p-value = 0.217).
- Among the predictors, the Saudi interest rate is statistically significant at the 5% level (p = 0.034).
- Oil price, Saudi inflation, and USD/SAR exchange rate are not statistically significant at the 5% level.

### MOEX Model

- The model explains approximately 14.1% of the variation in MOEX (R² = 0.141).
- The overall regression model is not statistically significant at the 5% level (F-test p-value = 0.300).
- None of the predictors are statistically significant at the 5% level.

### Multicollinearity

VIF values are close to 1 for all predictors in both models, suggesting no substantial multicollinearity among the explanatory variables.

## Project Structure

```text
macroeconomic-data-analysis/
│
├── README.md
├── macroeconomic_analysis.ipynb
└── macroeconomic_data.csv

```text
## Visualizations

### TASI Index Trend

![TASI Index Trend](./visualizations/TASI%20Index%20Trend.png)

### MOEX Index Trend

![MOEX Index Trend](./visualizations/MOEX%20Index%20Trend.png)

### Oil Price vs TASI

![Oil Price vs TASI](./visualizations/Oil%20Price%20vs%20TASI.png)

### Oil Price vs MOEX

![Oil Price vs MOEX](./visualizations/Oil%20Price%20vs%20MOEX.png)

### Correlation Matrix

![Correlation Matrix](./visualizations/Correlation%20Matrix.png)
