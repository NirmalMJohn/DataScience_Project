# DataScience_Project 
# Title: Multivariate Forecasting Models & Optimization Algorithm for Electricity Load
## Overview
This project aims to forecast energy consumption for different consumer archetypes using Long Short-Term Memory (LSTM) neural networks and SARIMAX models. Additionally, the project involves optimizing the forecasted load under Time-of-Use (TOU) tariffs using Linear Programming (LP) to minimize electricity costs.

## Project Structure
## Data Preparation:

The dataset includes energy consumption and weather data for forecasting consumer archetype based load.
Consumer archetype Cluster 01 is further merged its base & peak load and Tariff price for optimization
## Forecasting:
**LSTM Model**: A neural network model trained to predict future energy consumption based on historical data.

**SARIMAX Model**: A statistical model used to forecast energy consumption while accounting for seasonality and exogenous variables like temperature.
Forecasts from both models are generated for each consumer archetype.
## TOU Tariff Optimization:
The forecasted loads are adjusted using Linear Programming to minimize electricity costs under the given TOU tariff structure.
Constraints include peak and base load values specific to each day.

## Files in the Repository
Main_Forecasting_LP.ipynp is the final file that needs to be executed.

## Data Source Link
Smartmeter data & tariff data: https://data.london.gov.uk/dataset/smartmeter-energy-use-data-in-london-households 
Weather data: https://open-meteo.com/en/docs 
Use following latitude and longitude for the temperature data of London
latitude	longitude
51.493847	-0.1630249

