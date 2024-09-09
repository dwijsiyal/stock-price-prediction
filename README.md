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

### **EDA:**
The Exploratory Data Analysis shows a strong positive relation between variables of Stock, which indicates stability in the stock price that is if any one varibale increases the other variables increase as well.


![image](https://github.com/user-attachments/assets/233420f9-d147-4d08-8a34-aa1359642dfc)

![image](https://github.com/user-attachments/assets/4d529b26-95ec-4c34-a9bf-7e594db45b9d)


![image](https://github.com/user-attachments/assets/6607b445-d17f-46f2-9d41-b2eb4042146b)

![image](https://github.com/user-attachments/assets/d89dbb64-f576-478c-8904-ca8f79629aab)

![image](https://github.com/user-attachments/assets/b904d721-abae-4d0c-92bb-ab96bd735f62)

![image](https://github.com/user-attachments/assets/d61f29a2-88dd-41d6-b05a-92d5f9696db2)

![image](https://github.com/user-attachments/assets/7f029bcd-7b53-45d5-96f6-eaa2cc447152)

### Anamoly Detection:
#### Sign1 method:
![image](https://github.com/user-attachments/assets/bff3bb16-cfad-4311-881e-92efde61e12d)

#### Sign2 method:
![image](https://github.com/user-attachments/assets/fa90c56c-8563-4e6e-b78b-3bc5d2051464)

#### pcout method:
![image](https://github.com/user-attachments/assets/0c541910-b0b1-4d73-adc2-fddcba61ce69)

### Forecasting:
#### Estimating ARIMA variables for predictive modeling:
- 3rd order differencing to stationarize the Time Series
  ![image](https://github.com/user-attachments/assets/0ce45597-1939-4f08-b1ad-1253a51a70b7)

- Autocorelation value 3
  
  ![image](https://github.com/user-attachments/assets/250fc589-7dff-4167-99ad-e8cfa8fcfe02)

- Partial autocorelation value 2
  
  ![image](https://github.com/user-attachments/assets/1c102b4c-38c8-41a1-9fcb-5edb7f047edc)

#### Error calculation:
![image](https://github.com/user-attachments/assets/274ae78a-3e4d-4e61-9120-0338a456427c)

#### Multistep Predicition:
![image](https://github.com/user-attachments/assets/9b1bcc25-5c7c-4950-a0a6-10191c937339)


![image](https://github.com/user-attachments/assets/b629c8d1-5243-4f53-9e48-d35687524e04)


![image](https://github.com/user-attachments/assets/a927d6eb-a322-447d-9451-bc5722dbc6c4)


![image](https://github.com/user-attachments/assets/ee2f6cf6-5a60-4075-ab52-fd9bddb9b85a)



## 6. **Conclusion**
The analysis indicates consistent trends in Zomato's stock prices, providing valuable insights for investors. The identified anomalies and forecasted trends are crucial for strategic investment planning.

