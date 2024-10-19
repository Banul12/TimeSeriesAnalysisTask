Stock Price Time Series Analysis

This project involves time series analysis of stock prices using Python. The dataset contains stock data over a 5-year period, and the analysis includes various techniques such as seasonal decomposition, moving averages, and anomaly detection.
Features

    Data Loading and Preprocessing:
        Loaded the stock price data from a CSV file.
        Converted the 'date' column to datetime format and set it as the index.

    Time Series Plot:
        Plotted the close prices over time to visualize stock trends.

    Seasonal Decomposition:
        Decomposed the time series into trend, seasonality, and residuals using statsmodels' seasonal_decompose.

    Moving Average:
        Calculated and plotted a 30-day moving average to smooth the series.

    Anomaly Detection:
        Identified anomalies in stock prices using z-scores of residuals and highlighted them on the plot.

Dependencies

    pandas
    matplotlib
    statsmodels
    numpy

Visualization

The project includes visualizations for:

    Stock prices over time.
    Moving average overlay on the original price.
    Seasonal decomposition.
    Anomalies highlighted in the residuals.
