# Forecasting-Bus-Demand-in-Banana-Republic-Municipalities
The central urban planning commitee of Banana Republic asked you to help them with the forecast of bus demands of municipalities. And they provide a nice dataset to support you (https://pi.works/3w8IJbV).
The dataset includes two measurements for an hour for the number of used buses in each municipality, each measurement is timestamped. The dataset format is as follows (comma separated values):

MUNICIPALITY_ID, TIMESTAMP, USAGE, TOTAL_CAPACITY
- You may look at the one of the solution approach found in kaggle using the link: https://www.kaggle.com/code/berkantaslan/forecasting-bus-demand-in-banana-municipalities/notebookApplication 
- Forecasting of hourly different buses usages has been predicted by the time series solution using LSTM in Tensorflow.

Model, built in TensorFlow using LSTM layers, may give you an insight into a solution to forecast usage quantity.
The model can be improved using different layers, dropouts, batch size, optimizer, or epoch parameters.It was created with the aim of giving an idea about how LSTM is used in tensorflow application.
