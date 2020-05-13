# Time-Series-Analysis_Natural-Gas

The purpose of this project
> To find price distribution for planing trading zone

> To find daily return of Natural Gas for setting Target profit

> To find Natural Gas Seasonality for allocating cash to this asset before price rising due to 
natural gas demand 

Data set info: source of data set from investing.com, freq. daily data set periods from 1990-2020

Description
the framework of this project start with exploratory data analysis to find price distribution to specify
trading range and daily return distribution for setting proper target price when start to trading. Then use
Time series analysis to decompose historical price. Find seasonality, what month I can start to allocate cash
to natural gas before price rising due to high demand. The last process, use many techniques for forecasting 
as following

>Simple Moving Average

>Exponential Weight Moving Average

>Double Exponential Smoothing

>Tripple Exponential Smoothing

>ARIMA

All techniques are evaluated with Mean Square Error (MSE) to compare which one is the best to explain natural gas
behavior. The final step forecast natural gas price in the next 12 month
