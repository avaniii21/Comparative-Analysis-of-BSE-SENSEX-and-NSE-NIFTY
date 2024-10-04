# Comparative-Analysis-of-BSE-SENSEX-and-NSE-NIFTY

Stock Price Prediction using ARIMA and SARIMA Models
Overview
This project focuses on forecasting stock prices of India's major indices, NSE Nifty and BSE Sensex, using ARIMA (AutoRegressive Integrated Moving Average) and SARIMA (Seasonal ARIMA) models. The goal of this project is to analyze historical stock data from 2019 to 2024 and predict future prices with high accuracy by capturing both seasonal and non-seasonal patterns in the data.

Features
Time series analysis of stock data for NSE Nifty and BSE Sensex
Implementation of ARIMA and SARIMA models for accurate stock price forecasting
Data preprocessing, including handling missing values and data normalization
Seasonal pattern detection and integration into the prediction model
Visualization of historical and predicted stock prices
Achieved prediction accuracy of around 94%
Data Sources
The historical stock data for this project was sourced from publicly available databases and includes:

NSE Nifty (2019 - 2024)
BSE Sensex (2019 - 2024)
Model Details
ARIMA (AutoRegressive Integrated Moving Average): Captures non-seasonal trends and patterns in the stock data.
SARIMA (Seasonal ARIMA): Extends ARIMA by capturing seasonal variations along with trends, making it suitable for the cyclic nature of stock prices.
Key Parameters:
p: The number of lag observations
d: The number of times the data needs to be differenced to make it stationary
q: The size of the moving average window
P, D, Q, m: Seasonal components for SARIMA


Here's a README template for your ARIMA and SARIMA Stock Price Prediction project:

Stock Price Prediction using ARIMA and SARIMA Models
Overview
This project focuses on forecasting stock prices of India's major indices, NSE Nifty and BSE Sensex, using ARIMA (AutoRegressive Integrated Moving Average) and SARIMA (Seasonal ARIMA) models. The goal of this project is to analyze historical stock data from 2019 to 2024 and predict future prices with high accuracy by capturing both seasonal and non-seasonal patterns in the data.

Features
Time series analysis of stock data for NSE Nifty and BSE Sensex
Implementation of ARIMA and SARIMA models for accurate stock price forecasting
Data preprocessing, including handling missing values and data normalization
Seasonal pattern detection and integration into the prediction model
Visualization of historical and predicted stock prices
Achieved prediction accuracy of around 94%
Data Sources
The historical stock data for this project was sourced from publicly available databases and includes:

NSE Nifty (2019 - 2024)
BSE Sensex (2019 - 2024)
Model Details
ARIMA (AutoRegressive Integrated Moving Average): Captures non-seasonal trends and patterns in the stock data.
SARIMA (Seasonal ARIMA): Extends ARIMA by capturing seasonal variations along with trends, making it suitable for the cyclic nature of stock prices.
Key Parameters:
p: The number of lag observations
d: The number of times the data needs to be differenced to make it stationary
q: The size of the moving average window
P, D, Q, m: Seasonal components for SARIMA

Results
The project successfully predicted stock prices with an accuracy of approximately 94%, making it a reliable model for financial market forecasting.

Example Visualization:
Historical and predicted stock prices plotted over time for both NSE Nifty and BSE Sensex.
Future Work
Explore the integration of more complex machine learning algorithms, such as LSTM, to further improve accuracy.
Expand the analysis to include additional stock indices or international stock markets.
