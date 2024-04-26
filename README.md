# Sales Forecasting for Walmart Using Time Series Analysis

This project is part of my MBA program, where I aim to apply data science techniques to real-world business problems. The focus of this project is on sales forecasting using time series analysis, specifically aiming to predict sales during holiday periods. The dataset used comprises historical sales data from Walmart stores across various locations.

*Orientator: Francisco Aparecido Rodrigues, PhD*

## Objective
Our primary goal is to develop a time series model that can accurately predict future sales for Walmart, specially in holiday periods.

## Data
A rich dataset provided by Walmart on Kaggle has been used for this project. For more details about this dataset, visit the original link: [Walmart Sales Forecast Dataset](https://www.kaggle.com/datasets/aslanahmedov/walmart-sales-forecast)

## Data Dictionary
The datasets and its respective columns are as follows:

### features.csv
This file contains additional data related to the store, department, and regional activity for the given dates. It contains the following fields:
- **Store:** Store number
- **Date:** Week
- **Temperature:** Average temperature in the region
- **Fuel_Price:** Cost of fuel in the region
- **MarkDown1-5:** Anonymized data related to promotional markdowns that Walmart is running. More information on these features is not available
- **CPI:** The consumer price index, a measure that examines the weighted average of prices of a basket of consumer goods and services

### stores.csv
This file contains anonymized information about the 45 stores, indicating the type and size of the store:
- **Store:** Stores numbered from 1 to 45
- **Type:** Store type has been provided, there are 3 types — A, B and C
- **Size:** Stores size has provided from 34.9k to 220k
