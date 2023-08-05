# Kamogelo.github.io
Forecasting Daily Orders For Company X using time series models
This repository contains an R script that simulates and analyzes daily order data for two hypothetical express warehouses (EW1 and EW2). The script explores the data, forecasts daily orders for the next week, suggests the number of store operators needed based on the forecast, and measures the accuracy of the forecast.

#Data Simulation
The script simulates daily order data for the two express warehouses over a three-month period using a Poisson distribution. The average number of orders per day is set to 100 for EW1 and 150 for EW2.

# Data Exploration
The script provides a summary of the order data and plots the number of orders over time.

# Forecasting Daily Orders
The script uses the auto.arima function from the forecast package in R to forecast daily orders for the next week for each express warehouse. The forecasts are based on a time series of the order data, with a frequency of 7 to account for weekly patterns.

Suggesting Number of Store Operators
The script calculates the number of store operators needed for each express warehouse based on the forecasted number of orders and the capacity of a store operator (set to 70 orders per 8-hour shift).

# Forecasting Model Explanation and Suggestions
The script explains the choice of the ARIMA forecasting model and suggests other metrics or features that could be considered for forecasting, such as historical promotional activities, external factors like holidays or events, and order lead time or arrival patterns.

# Measuring Forecasting Accuracy
The script calculates the accuracy of the forecasts using the actual order data for the next week (assuming this data is available).

# Report Generation
The script generates a report summarizing the findings and saves it as a PDF file.

This project provides a practical example of data simulation, time series analysis, and forecasting in R. It can be used as a starting point for similar projects or as a teaching tool for these topics.
