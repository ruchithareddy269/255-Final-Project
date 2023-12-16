# CMPE255-Forecasting Bicycle Rentals-Time series analysis

| Project Members |
| ------------- | 
| Koluguri Ruchitha Reddy | 
| Suresh Ravuri | 
| Harshavardhan Raghavendra Valmiki |

## Introduction
Time-series analysis has long been a favored method in various fields, aiming to predict changes occurring over time. Its core purpose lies in utilizing historical data to anticipate future patterns and shifts. This analytical approach finds application across diverse domains like retail market analysis, sales projections, stock market evaluations, and more. Specifically, our task involves forecasting the volume of bike rentals based on surrounding conditions. Each day of bike rentals yields a time-series dataset encompassing variables such as temperature, weather conditions, wind speed, and the number of customers renting bikes. Our analysis focuses on dissecting bike rental data, delving into factors like temperature, seasonal variations, weather nuances, and other pertinent aspects influencing rentals. Given the time-series nature of the dataset, our goal is to predict customer volumes by leveraging insights gleaned from historical data.

## Objective
To predict future demand for bike rental services, historical rental bike usage patterns are used. Project Goals: Use a variety of machine learning techniques to forecast and evaluate model performances. Our objective is to project the number of patrons who will rent bicycles in light of the surrounding circumstances. Every time a customer rents a bike for the day, we maintain a record of it.

## Data Cleaning and Preparation: 
We cleaned the time-series data by removing null values and filling in missing values using methods like forward filling, especially important for maintaining data continuity and integrity.
## Feature Engineering:
New features were created by categorizing similar weather conditions and extracting date-related variables, enhancing the dataset for a more in-depth analysis of customer behavior patterns.
## Data Analysis and Visualization:
Various plots were utilized to visually analyze the dataset, aiding in the identification of trends, patterns, and insights that are vital for understanding the underlying data.
## Time Series Specific Analysis:
Recognizing the dataset as time-series data, we focused on assessing its stationarity through visual methods like line plots, a crucial step for appropriate model selection.
## Further Statistical Analysis: 
To ensure the accuracy of our time-series analysis, we planned to use advanced statistical tests, specifically the Augmented Dickey-Fuller (ADF) and Kwiatkowski-Phillips-Schmidt-Shin (KPSS) tests, to rigorously assess if the data was stationary.

## Dataset Resource: 
https://www.openml.org/search?type=data&status=active&id=43486&sort=runs

