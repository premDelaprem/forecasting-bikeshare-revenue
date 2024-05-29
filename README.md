# Building an ARIMA Model to Forecast Bike Share Revenue (README in progress)

## Overview
In this project, I thoroughly clean bike-share data from 2014-2015 to build a simplistic ARIMA model to forecast daily revenue per bike station in 2016. I also clean a complementary weather dataset consisting of potential exogenous variables that may prove useful in a future project to improve the forecast. <br>

After cleaning the datasets, I dive into building a relatively simple ARIMA model with seasonality (SARIMA). I discuss several considerations involving SARIMA, including which hyperparameters to tune and why log transforming revenue data may prove useful. I conclude with a single model that I extend to all other bike stations.


## Data
The `bike_trip_data.csv` consists of raw daily trip data across all bike stations in Austin, TX for the years 2014-2015. The `weather_data.csv` contains a time-series of daily weather data from 2014-2016. The weather data contains several exogenous variables such as average humidity, average temperature, and weather events (rain, fog, etc). 


## Modeling

