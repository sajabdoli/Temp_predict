# Time series prediction

This repo contains a notebook that demonstrates a simple prediction model based on an LSTM. The input data is a CSV file consisting of recordings of room temperature from both inside and outside.

For more information on the data and downloading please refer to: https://www.kaggle.com/datasets/atulanandjha/temperature-readings-iot-devices

For this project, we consider the temperature from inside the room. The data is recorded every minute. A sequence of 10 recordings is used to predict the immediate future. This number is adjustable.

These features are used for prediction:

> 'year', 'month', 'weekday', 'hour', 'minute', 'season', 'timing'

It is a naive feature selection. More features might be extracted from the raw data or we may reduce this set. A good approach might be using the ANOVA table for the best features selection. 
