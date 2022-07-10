# ML_Air_pollution_forecasting

## Goal
Air pollution forecasting using multivariate LSTM and GRU model.

## Dataset 
This is a dataset that reports on the weather and the level of pollution each hour for five years at the US embassy in Beijing, China.
The data includes the date-time, the pollution called PM2.5 concentration, and the weather information including dew point, temperature, pressure, 
wind direction, wind speed and the cumulative number of hours of snow and rain.

## EDA

### Correlation Matrix 

<img src="https://github.com/immayankprakash/ML_Air_pollution_forecasting/blob/master/images/Correlation.png" >

### Pollution breakdown 
<img src="https://github.com/immayankprakash/ML_Air_pollution_forecasting/blob/master/images/pollution.png" >

## Model

| Method  | Number |
| ------------- | ------------- |
| RNN(LSTM,GRU)  | 1 layer  |
| Optimizer  | adam  |
| Batch size  | 72 |
| Nodes   |  64   |
| MSE  | 5.55(LSTM), 0.98(GRU) |
| MAE  | 1.36(LSTM), 0.61(GRU) |

## Results
Air pollution forecasting using LSTM:

<img src="https://github.com/immayankprakash/ML_Air_pollution_forecasting/blob/master/images/validation_lstm.png" >

Air pollution forecasting using GRU:

<img src="https://github.com/immayankprakash/ML_Air_pollution_forecasting/blob/master/images/validation_gru.png" >
