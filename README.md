# LSTM
The goal of this task is to train a LSTM model that does single time weather predictions
# Introduction
This project aims to predict weather conditions on random days using Long Short-Term Memory (LSTM) networks. It involves analyzing and visualizing weather features, calculating correlation matrices, and building predictive models using LSTM networks.

# Features
Correlation Matrix Visualization: Visualize the correlation between different weather features.

LSTM Model for Prediction: Build and train an LSTM network to predict weather conditions.

Data Visualization: Raw data visualization for initial analysis.

# Data
The project uses a dataset containing various weather features. <br>

The main features include:<br>
Pressure<br>
Temperature<br>
Temperature in Kelvin<br>
Temperature (dew point)<br>
Relative Humidity<br>
Saturation vapor pressure<br>
Vapor pressure<br>
Vapor pressure deficit<br>
Specific humidity<br>
Water vapor concentration<br>
Airtight<br>
Wind speed<br>
Maximum wind speed<br>
Wind direction in degrees<br>

# Model Architecture
The model architecture consists of:<br>

Input Layer: Accepts sequences of weather data.<br>
LSTM Layer: Processes the input sequences to capture temporal dependencies.<br>
Dense Layer: Outputs the prediction for the weather condition.<br>

# Results
The project outputs include:<br>
Correlation matrix of the weather features.<br>
Visualization of raw weather data.<br>
Predicted weather conditions using the trained LSTM model.<br>
