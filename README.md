# ARIMA model
ARIMA stands for autoregressive integrated moving average.
This model takes in three parameteres - p, d, q
 - p - lag order (order of AR term)  – number of lagged observations used
 - d - degree of differencing (order of I term) – number of times observations are differenced to make it stationary
 - q - order of moving average (order of MA term) – moving window size or number of lagged forecast errors to be considered for training the model

# About
This project displays how an ARIMA model works using a dataset of monthly shampoo sales.

# Update
This project will encompass an amalgamation of all variants of ARIMA like ARMA, SARIMA, ARIMAX etc., to create a generic library for exploring, analyzing, cleaning, and predicting time series.
The aim of this project is to allow a raw CSV file to be input. The user defines the column names to be considered for performing functions like cleaning, explorations and analysis using visualisations and eminent statistical tests, and eventually predicting data.
The predictions will be generated using ARIMA models or one of its variants generalised as per use case.
The ARIMA modelling will include p, d, q optimisation using algorithms like grid-search.

# Challenges
Enable the library to be used for streaming data which involves deciding how to efficiently train the models.
