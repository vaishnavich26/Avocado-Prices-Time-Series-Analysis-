# Avocado-Prices-Time-Series-Analysis-
ARIMA SARIMA models for Avocado Price Prediction 

## Abstract

In an era where data-driven decision-making is paramount, accurate forecasting stands as a critical tool for market analysis and strategic planning. This project is anchored in the aim to forecast the average price of avocados using time series analysis, leveraging historical sales data to predict future market trends. The dataset underpinning this study encompasses a range of attributes from the date of observation to the distribution of sales across different avocado types and bag sizes, including both conventional and organic categories, across various regions and years.
We delve into time series decomposition, investigating patterns within the average price fluctuations over time. Through rigorous preprocessing steps including logarithmic transformations and differencing, we address non-stationarity — a typical challenge in time series forecasting. By deploying ARIMA, SARIMA, and LSTM models, we juxtapose traditional statistical approaches with advanced deep learning techniques, evaluating their predictive performances using the Root Mean Square Error (RMSE) metric.
Our research navigates through complex seasonal behaviors and shifting consumer preferences, offering insights into the avocado market dynamics. The outcomes of this study are not only expected to bolster the accuracy of price forecasting but also to contribute to the nuanced understanding of demand elasticity influenced by temporal trends. The implications of this work resonate with agricultural producers, retailers, and policy-makers who stand to benefit from precise market forecasts.
## Problem Statement

Avocado prices are notorious for their volatility, influenced by a myriad of temporal factors such as seasonality, economic trends, and consumer preferences. The challenge lies in developing accurate forecasting models that can decipher these temporal intricacies, empowering stakeholders to anticipate price fluctuations and strategize accordingly. This project aims to harness the power of time series analysis techniques to predict the average price of avocados, utilizing a comprehensive dataset encompassing various attributes including volume, type, and region. By delving into statistical tests for time series analysis, exploring the nuances of ARIMA and SARIMA models, and deploying in-sample and out-of-sample forecasting methodologies, this project endeavors to equip stakeholders with actionable insights for effective pricing strategies, inventory management, and market trend analysis.
## Dataset Information


The dataset for this study was meticulously sourced from the Hass Avocado Board, providing a comprehensive view of avocado sales dynamics across the United States. It spans several years and includes granular details that capture the essence of market fluctuations and consumer behavior over time. The attributes encapsulated within this dataset are as follows:
Date: Representing the date of observation, this field is fundamental for the time series analysis, enabling the chronological ordering of price movements and volume sales.
AveragePrice: A critical metric that represents the average price of a single avocado, it serves as the target variable for our forecasting models.
Total Volume: Aggregating the total sales volume of avocados, this attribute provides insight into the overall market demand.
PLU-Based Sales Breakdown (4046, 4225, 4770): These attributes detail the sales volumes of avocados differentiated by their Product Lookup Codes (PLUs), which correspond to specific avocado types and sizes, enabling an analysis of consumer preferences for particular avocado varieties.
Bagging Breakdown (Total Bags, Small Bags, Large Bags, XLarge Bags): This categorization offers a window into packaging trends and the popularity of different bag sizes, which can reflect marketing effectiveness and consumption patterns.
Type: Distinguishing between conventional and organic produce, this factor allows for a comparative analysis of these two significant market segments.
Year: The year of observation is crucial for understanding long-term trends and annual patterns in avocado pricing and sales.
Region: Providing geographical granularity, this attribute spans various cities and regions, shedding light on localized market behaviors and potential regional preferences.
By harnessing data from the Hass Avocado Board, our analysis benefits from a dataset rich in detail and relevance, ensuring that our forecasts are grounded in real-world patterns and market behaviors.
