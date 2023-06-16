# Temperature_Forecasting_with_LSTM

The project aims to develop an LSTM-based temperature forecasting model using the Jena Climate dataset. The Jena Climate dataset contains various weather measurements recorded over several years. The goal is to train an LSTM neural network to predict future temperature values based on historical data.

The LSTM model, a type of recurrent neural network (RNN), is well-suited for capturing temporal dependencies in time series data. By processing the sequential data, the model can learn patterns and relationships in the temperature measurements over time.

The project involves several steps, including data loading, preprocessing, splitting into training and testing sets, and scaling the data. The LSTM model is built using the Keras library, with appropriate layers and architecture. The model is then trained using the training data and evaluated using metrics like RMSE to assess its performance. Root Mean Squared Error score is 0.5778
