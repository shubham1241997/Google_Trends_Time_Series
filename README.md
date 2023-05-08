# Google_Trends_Time_Series
Google Trends gives us an estimate of search volume. Let's explore if search popularity relates to other kinds of data. Perhaps there are patterns in Google's search volume and the price of Bitcoin or a hot stock like Tesla. Perhaps search volume for the term "Unemployment Benefits" can tell us something about the actual unemployment rate?
\

What can the popularity of search terms tell us about the world? Google Trends gives us access to the popularity of Google Search terms. Let's investigate:

1. How search volume for "Bitcoin" relates to the price of Bitcoin
2. How search volume for a hot stock like Telsa relates to that stock's price and
3. How searches for "Unemployment Benefits" vary with the actual unemployment rate in the United States

learning :
1. How to make time-series data comparable by resampling and converting to the same periodicity (e.g., from daily data to monthly data).
2. Fine-tuning the styling of Matplotlib charts by using limits, labels, linestyles, markers, colours, and the chart's resolution.
3. Using grids to help visually identify seasonality in a time series.
4. Finding the number of missing and NaN values and how to locate NaN values in a DataFrame.
5. How to work with Locators to better style the time axis on a chart


Data Sources:

1. Unemployment Rate from FRED
2. Google Trends
3. Yahoo Finance for Tesla Stock Price
4. Yahoo Finance for Bitcoin Stock Price

required libraries

1. import pandas as pd  
2. import matplotlib.pyplot as plt
3. import matplotlib.dates as mdates 
