# LSTM
The goal of this task is to train a LSTM model that does single time weather predictions
# Introduction
This project aims to predict weather conditions on random days using Long Short-Term Memory (LSTM) networks. It involves analyzing and visualizing weather features, calculating correlation matrices, and building predictive models using LSTM networks.

# Table of Contents
Introduction
Features
Data
Model Architecture
Results

# Features
Correlation Matrix Visualization: Visualize the correlation between different weather features.

LSTM Model for Prediction: Build and train an LSTM network to predict weather conditions.

Data Visualization: Raw data visualization for initial analysis.

# Data
The project uses a dataset containing various weather features. The main features include:

Pressure
Temperature
Temperature in Kelvin
Temperature (dew point)
Relative Humidity
Saturation vapor pressure
Vapor pressure
Vapor pressure deficit
Specific humidity
Water vapor concentration
Airtight
Wind speed
Maximum wind speed
Wind direction in degrees

# Model Architecture
The model architecture consists of:

Input Layer: Accepts sequences of weather data.
LSTM Layer: Processes the input sequences to capture temporal dependencies.
Dense Layer: Outputs the prediction for the weather condition.

# Results
The project outputs include:

Correlation matrix of the weather features.
Visualization of raw weather data.
Predicted weather conditions using the trained LSTM model.
