📊 Analyzing the US Stock Market and Commodities Data (2020–2024)
Overview
This project presents a comprehensive analysis of the US stock market and major commodities between 2020 and 2024. Using advanced statistical methods and machine learning models, we analyze historical trends, interdependencies, the impact of external events (notably COVID-19), and forecast future market movements. The study offers actionable insights into market behavior during periods of heightened volatility and transformation.

Authors
Srihari Kamath

Ashtavinayak Pande

Chinmay Shanbhag

Project Objectives
Trend Analysis: Identify long-term patterns and cyclical behaviors in stock and commodity prices.

Correlation Analysis: Understand interdependencies among selected stocks and commodities.

Event Impact Assessment: Analyze the market impact of major global events, particularly the COVID-19 pandemic.

Forecasting: Develop predictive models to forecast future price movements based on historical data.

Methodology
Data Collection and Preprocessing
Source: US Stock Market Dataset (Kaggle)

Cleaning:

Removed irrelevant columns.

Imputed missing values using mean substitution.

Standardized date formats for time series consistency.

Exploratory Data Analysis (EDA)
Generated visual summaries of stock and commodity price movements.

Analyzed distributions, trends, and preliminary correlations across variables.

Trend Analysis
Applied Linear Regression models to assess directional trends in Apple's stock price and trading volume.

Event Impact Analysis
Segmented data into distinct COVID-19 phases (pre-pandemic, first wave, second wave, Omicron wave).

Evaluated volatility and recovery patterns for key market indicators (Apple Inc., S&P 500).

Forecasting
Implemented:

LSTM (Long Short-Term Memory) neural networks.

ARIMA and SARIMA time-series models.

Model performance evaluated using:

MAPE (Mean Absolute Percentage Error)

SMAPE (Symmetric Mean Absolute Percentage Error)

Key Findings

Aspect	Findings
Stock Trends	Apple's stock price exhibited a steady upward trend, while trading volumes gradually declined.
Event Impacts	Market volatility peaked during COVID-19 waves but showed remarkable recovery post-pandemic.
Forecasting	LSTM models demonstrated superior predictive performance (Test MAPE ≈ 5%), outperforming traditional ARIMA/SARIMA approaches.
Technologies Used
Python

Libraries:
Pandas, Matplotlib, Seaborn, Scikit-learn, TensorFlow/Keras, Statsmodels

Techniques:

Linear Regression

Time-Series Forecasting (LSTM, ARIMA, SARIMA)

Event-driven Market Analysis


Future Work
Normalized Analysis: Focus on percentage price changes rather than absolute values for better cross-stock comparisons.

Market Efficiency Testing: Implement Random Walk Hypothesis models to further assess predictability.

Enhanced Feature Sets: Incorporate macroeconomic indicators (e.g., inflation rates, unemployment data) for improved forecasting accuracy.

References
US Stock Market Dataset (Kaggle)

IBM - Introduction to Linear Regression

Financial Data Analysis Techniques (LinkedIn)

Wikipedia - ARIMA

Acknowledgments
We extend our gratitude to the Kaggle community for providing the dataset and to the broader financial research community for developing robust methods to understand market behavior under uncertainty.

