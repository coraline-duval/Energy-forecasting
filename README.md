# Energy-forecasting

The goal was to predict the energy load of the UK national gric twice weekly for the day +1 and day +2 during 3 weeks in 2021.
We used the daily electricity loads over 3 years as a baseline, the covid-19 crisis infection numbers, and the sunshine duration and temperature of each day.
We used a multiple linear regression, a SARIMA, a neural network (MLPRegressor), a Recurrent neural network (LSTM) to try and predict the daily energy load.
The multiple regression model and neural network had similar results, however, the mutliple regression model was much faster to train.
