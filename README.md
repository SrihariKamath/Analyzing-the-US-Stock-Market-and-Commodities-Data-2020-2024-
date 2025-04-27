# 📊 Analyzing the US Stock Market and Commodities Data (2020–2024)

## Overview
This project presents a comprehensive analysis of the US stock market and major commodities between 2020 and 2024. Using advanced statistical methods and machine learning models, we analyze historical trends, interdependencies, the impact of external events (notably COVID-19), and forecast future market movements. The study offers actionable insights into market behavior during periods of heightened volatility and transformation.

## Authors
- Srihari Kamath
- Ashtavinayak Pande
- Chinmay Shanbhag

## Project Objectives
- Conduct trend analysis on stock prices and commodities.
- Explore correlations between stocks and commodities.
- Assess the impact of major events (e.g., COVID-19 pandemic) on market behavior.
- Develop forecasting models to predict future price movements based on historical data.

## Methodology

### Data Collection and Preprocessing
- **Source**: [US Stock Market Dataset (Kaggle)](https://www.kaggle.com/datasets/dhavalpatel555/us-stock-market-2020-to-2024)
- **Cleaning**:
  - Removed irrelevant columns (e.g., `Platinum_Vol`, `Unnamed:0`).
  - Imputed missing values using mean substitution.
  - Standardized date formats for time series consistency.

### Exploratory Data Analysis (EDA)
- Generated visual summaries of stock and commodity price movements.
- Analyzed distributions, trends, and preliminary correlations across variables.

### Trend Analysis
- Applied **Linear Regression** models to assess directional trends in Apple's stock price and trading volume.

### Event Impact Analysis
- Segmented data into distinct COVID-19 phases (pre-pandemic, first wave, second wave, Omicron wave).
- Evaluated volatility and recovery patterns for key market indicators (Apple Inc., S&P 500).

### Forecasting
- Implemented:
  - **LSTM (Long Short-Term Memory)** neural networks
  - **ARIMA** and **SARIMA** time-series models
- Model performance evaluated using:
  - **MAPE** (Mean Absolute Percentage Error)
  - **SMAPE** (Symmetric Mean Absolute Percentage Error)

## Key Findings

| Aspect                  | Findings |
|--------------------------|----------|
| **Stock Trends**         | Apple's stock price exhibited a steady upward trend, while trading volumes gradually declined. |
| **Event Impacts**        | Market volatility peaked during COVID-19 waves but showed remarkable recovery post-pandemic. |
| **Forecasting**          | LSTM models demonstrated superior predictive performance (Test MAPE ≈ 5%), outperforming traditional ARIMA/SARIMA approaches. |

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - TensorFlow/Keras
  - Statsmodels
- **Techniques**:
  - Linear Regression
  - Time-Series Forecasting (LSTM, ARIMA, SARIMA)
  - Event-driven Market Analysis

## Repository Structure
├── US_Stock.ipynb # Main Jupyter Notebook containing the full analysis 

├── README.md # Project documentation 

├── data/ # Source and processed datasets

## Future Work
- Focus on **percentage change analysis** for better normalized comparisons across different stocks and commodities.
- Implement **Random Walk Hypothesis** models to assess market efficiency.
- Incorporate broader macroeconomic indicators (e.g., inflation, GDP growth) into forecasting models.

## References
- [US Stock Market Dataset (Kaggle)](https://www.kaggle.com/datasets/dhavalpatel555/us-stock-market-2020-to-2024)
- [IBM - Introduction to Linear Regression](https://www.ibm.com/topics/linear-regression)
- [Financial Data Analysis Techniques (LinkedIn)](https://www.linkedin.com/advice/3/how-do-you-analyze-financial-data-skills-data-analytics)
- [Wikipedia - ARIMA](https://en.wikipedia.org/wiki/Autoregressive_integrated_moving_average)

## Acknowledgments
We extend our gratitude to the Kaggle community for providing the dataset and to the broader financial research community for developing robust methods to understand market behavior under uncertainty.
