# Sensor data anomoly detection using Time series analysis
## Description
This project is a beginners project to perform time series analysis using python for detecting anomalies in multi sensor indoor environmental data. The data is not a real world data, but mimics a real world data set by simulating a set of sensor values against time calculated for a day.

## What is time series analysis
A time series is a sequence of data points recorded at regular time intervals. Time Series Analysis is the study of data points collected over time to identify patterns, trends, and seasonal variations. It is widely used in weather forecasting, stock market analysis, energy consumption tracking, and IoT sensor data processing.

## Methodology of the project
1. Create a time / date object in python
2. Simulate temperature, humidity and light sensor data
3. Build a data frame
4. Visualize sensor data vs time
5. Remove noise, and learn on trends
6. Detect anomolies in sensor data
7. Perform simple forecasting using SMA (Simple moving average)

## Description
1. **Create a time object:** We create a 24 hour time log, which creates a time stamp for every minute using the 'Date range method' of pandas library. Creates a series of time stamps for a 
   day.
2.** Create a simulated real world sensor data**: We create a simple dataset comprising of temperature, humidity and light data. 
