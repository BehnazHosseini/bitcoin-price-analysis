# Bitcoin Price Analysis and Forecasting: Volatility Insights, Time Series Modeling, and Visualization

## Overview

Bitcoin, the pioneering cryptocurrency, has ignited global interest due to its intriguing price fluctuations and potential impact on the financial landscape. This project is designed to provide a comprehensive exploration of Bitcoin's price behavior, encompassing historical trends, volatility patterns, and future price predictions.

**Note**: You can see the code in bitcoin.ipynb and the notebook with outputs and plots in bitcoin_notebook.html.

## Table of Contents

- [Data](#data)
- [Methodology](#methodology)
  - [Volatility Analysis](#volatility-analysis)
  - [Time Series Forecasting](#time-series-forecasting)
  - [Insights Extraction and Visualization](#insights-and-visualization)
- [Conclusions](#conclusions)

## Data

The foundation of this analysis rests on historical Bitcoin price data, meticulously collected from the CryptoCompare API. This dataset comprises of hourly Bitcoin price data starting from July 23, 2023, 23:00:00 and going back two years. The dataset encompasses a rich variety of information, including daily opening, closing, high, and low prices, along with corresponding trading volumes in Bitcoin and US Dollars. This comprehensive dataset serves as the bedrock for our in-depth analysis and forecasting endeavors.

## Methodology

### Insights and Visualization

Data visualization is a powerful tool for communicating complex insights. Leveraging the Plotly library, we create interactive visualizations that illuminate trends, highlight seasonal patterns, and showcase forecasted price trajectories. These visualizations help stakeholders comprehend Bitcoin's intricate behavior and make informed decisions.

### Volatility Analysis

Volatility analysis was conducted to explore the fluctuation patterns in Bitcoin prices over time. The data was resampled to different time intervals (daily and weekly) to assess volatility clustering and trends. Bollinger Bands were utilized to identify periods of high volatility and potential buy/sell signals. Exploring and understanding Bitcoin price volatility is crucial for risk assessment and informed decision-making in the cryptocurrency market.

### Time Series Forecasting

For time-series forecasting, three prominent models were employed: ARIMA (AutoRegressive Integrated Moving Average) SARIMA (Seasonal ARIMA) and Prophet. SARIMA is a well-established model for handling seasonality and trends, while Prophet offers flexibility and incorporates various factors.

The SARIMA model was tuned for optimal parameters (p, d, q) through a grid search approach, aiming to minimize the Mean Absolute Error (MAE) on the validation set. The Prophet model, on the other hand, was utilized to capture both trend and seasonal components while also allowing for the incorporation of additional regressors.

### Insights Extraction and Visualization
Visualizations played a crucial role in extracting insights from the data. Various plots were generated to depict volatility, trends, and the performance of forecasting models. Additionally, we examined autocorrelation and partial autocorrelation functions to aid in selecting appropriate lag orders.

## Conclusions
The project's findings shed light on Bitcoin's price volatility, historical trends, and potential future price movements. Through rigorous analysis and modeling, we gained insights into the complex nature of cryptocurrency markets. Future work could involve exploring more advanced forecasting models, incorporating external factors, and expanding the analysis to other cryptocurrencies.

The project's core findings and outcomes can be summarized as follows:

- Volatility Insights: Our examination of Bitcoin price volatility revealed intriguing volatility clustering patterns. These insights provide valuable information for understanding market behavior and making informed decisions within the cryptocurrency space.

- Predictive Modeling: By employing advanced time-series forecasting models like SARIMA and Prophet, we achieved successful predictions of Bitcoin prices into the future. This predictive capability equips us with a potential advantage for anticipating market trends.

- Interpreting Visuals: Beyond technical aspects, we emphasized the extraction of meaningful insights from visualizations. This combination of analytical skills and effective data communication enables us to decipher complex trends and patterns.

The combined use of volatility analysis, time-series modeling, and insightful visualization allowed us to understand and forecast Bitcoin price dynamics, contributing to a deeper understanding of the cryptocurrency landscape.
