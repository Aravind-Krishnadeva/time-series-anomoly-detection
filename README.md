# Sensor data anomoly detection using Time series analysis
## Description
This project is a beginners project to perform time series analysis using python for detecting anomalies in multi sensor indoor environmental data. The data is not a real world data, but mimics a real world data set by simulating a set of sensor values against time calculated for a day.

## What is time series analysis
A time series is a sequence of data points recorded at regular time intervals. Time Series Analysis is the study of data points collected over time to identify patterns, trends, and seasonal variations. It is widely used in weather forecasting, stock market analysis, energy consumption tracking, and IoT sensor data processing.

## Knowing time series patterns
![Time_series_data](https://github.com/user-attachments/assets/0be293db-a452-4c2f-a6e6-407911d717b8)

## Methodology of the project
1. Create a time / date object in python
2. Simulate temperature, humidity and light sensor data
3. Build a data frame
4. Visualize sensor data vs time
5. Remove noise, and learn on trends
6. Detect anomolies in sensor data
7. Perform simple forecasting using SMA (Simple moving average)

## Software requirements and environment
   1. Anaconda installation
   2. Jupyter notebooks for coding
   
## Description
## 1. Create a Time Object
Generate a 24-hour timeline with a timestamp for every minute using the `date_range()` method from the Pandas library. This forms the time base for our time series.

## 2. Simulate Real-World Sensor Data
Create synthetic datasets mimicking real sensor data — including temperature, humidity, and light intensity — with added random noise for realism.

## 3. Create a Time-Indexed DataFrame
Combine the time object and simulated data into a Pandas DataFrame, setting time as the index to enable time-based operations.

## 4. Initial Data Visualization
Plot the raw sensor data against time to observe natural trends and noise.

## 5. Apply Trend Smoothing
Use a Simple Moving Average (SMA) to smooth the time series, helping to highlight overall trends by reducing noise.

## 6. Smoothed Data Visualization
Plot the smoothed sensor data to compare with raw data and better understand the underlying patterns.

## 7. Perform Anomaly Detection
Identify abnormal sensor readings by comparing values against rolling statistics (mean and standard deviation).
