# Prediction of gas consumption

An example of using XGBoost regressor and simple neural network for predicting gas consumption for one client in Białystok.
Train data: 2019.01.01 - 2021.10.20
Test data: 2021.11.01 - 2022.02.28

Source data contains hourly consumption. The script converts it to daily consumption to make the daily prognosis.
The weather data (average temperature and average wind speed) is also used .
