# Product-Demand-Forecasting
## Abstract

Machine learning has revolutionized demand forecasting, enabling industries to navigate complexities with enhanced accuracy. Our study utilizes a vast historical dataset over six years from a manufacturing company to analyze and forecast product demand. Employing a systematic approach to data preparation and utilizing simple exponential smoothing methods, we offer strategic insights for future demand, underscoring the transformative potential of machine learning in strategic planning and operational efficiency.

## Introduction
This project aims to apply machine learning methodologies to predict future product demands based on historical data. The focus is on a dataset reflecting six years of operations within a manufacturing company, assessing patterns and trends that will assist in strategic decision-making. The investigation begins with data preparation, followed by exploratory graphics, and culminates in forecasting using exponential smoothing.

## Dataset
The dataset contains 1,048,575 entries from 2014 to 2019, including product codes, category codes, warehouse names, order dates, and demand. It's stored in five columns and has undergone extensive preprocessing to rectify anomalies like null values and incorrect dates. The modified dataset is integral to our analyses and forecasts. 

## Installation
To set up the project environment, ensure that Python and necessary libraries such as Pandas, NumPy, and Matplotlib are installed. 

## Data Preprocessing
Data cleaning involved removing entries with null order dates and setting negative demand values to zero. Non-existent dates in non-leap years were corrected to February 28th. The order date was converted to a datetime format, and additional columns for Month and Year were included for easier analysis.

## Analysis
Warehouse demand over years showed an increasing trend until 2018, with a decline in 2019. Category demand in the Brampton warehouse indicated that category 019 had significantly higher demand than others. The top 5 products in 2014 were identified and their demand trends analyzed over subsequent years.

## Forecasting Results
The forecast focused on the product with the highest demand in category 019 for 2019. An exponential smoothing model projected demand for the year 2020, taking into account trends and seasonality. The forecast for the next 12 months was visualized, demonstrating the anticipated cyclical demand.

## Conclusions
The project illustrates how machine learning can revolutionize demand forecasting in manufacturing, with exponential smoothing providing reliable future demand projections. The insights gained are pivotal for inventory management and operational efficiency, showcasing the importance of machine learning models in strategic planning in dynamic market environments.
