# Analyzing and Forecasting Zomato Stock Prices

## Abstract
This project addresses the volatility in Zomato's stock price since its IPO in July 2021. The analysis, covering data from July 2021 to February 2024, includes Exploratory Data Analysis (EDA), Anomaly Detection, Time Series Forecasting, and Result Visualization. These phases provide insights into stock price trends, identify anomalies, and forecast future stock prices to aid investors in making informed decisions.

## Table of Contents
1. Introduction
2. Problem Statement
3. Data Description
4. Methodology
   - Exploratory Data Analysis (EDA)
   - Anomaly Detection
   - Time Series Forecasting
   - Result Visualization
5. Results and Discussion
6. Conclusion
7. Appendices

## 1. Introduction
Zomato, founded in 2008, is an Indian multinational corporation specializing in restaurant aggregation and food delivery services. This project focuses on analyzing Zomato's stock price data from July 2021 to February 2024. The key objectives include detecting anomalies and developing predictive models using the ARIMA methodology.

## 2. Problem Statement
Despite Zomato's rapid growth, its stock price has shown significant volatility since its IPO, challenging investors in making informed decisions. This project aims to analyze Zomato’s stock price data to detect anomalies and forecast future trends, providing actionable insights for better investment strategies.

## 3. Data Description
The dataset, sourced from Kaggle, includes seven columns: Date, High, Open, Close, Low, Adj Close, and Volume. Data integrity checks and handling of missing values ensure the dataset's readiness for analysis.

## 4. Methodology
**4.1. Exploratory Data Analysis (EDA)**
**Data Inspection:** Initial examination for inconsistencies, missing values, or outliers.
**Descriptive Statistics:** Computation of statistical measures such as mean, median, and standard deviation.
**Column Distributions:** Visual representation using histograms.
**Scatter Plot Analysis:** Analysis of relationships between variables.

**4.2. Anomaly Detection**
Anomalies are identified using the Sign Method and PCOut method, crucial for forecasting future values due to market volatility.

**4.3. Time Series Forecasting**
The ARIMA model is used for forecasting future stock prices. Model parameters (p, d, q) are determined using ACF and PACF graphs, and the model's accuracy is evaluated using MAPE and RMSE.

**4.4. Result Visualization**
Results are visualized using line charts, histograms, scatter plots, and candlestick charts.

## 5. **Results and Discussion**
The EDA phase reveals a strong positive correlation between price variables. Anomaly detection shows that the stock market data's inherent volatility includes anomalies that should not be removed.

## 6. **Conclusion**
The analysis indicates consistent trends in Zomato's stock prices, providing valuable insights for investors. The identified anomalies and forecasted trends are crucial for strategic investment planning.

