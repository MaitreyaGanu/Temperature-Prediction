# Temperature Prediction Using LSTM

This project demonstrates the use of Long Short-Term Memory (LSTM) networks to predict the daily temperatures in Seattle. The dataset is preprocessed by using a **7-day moving average** to smooth the data and capture long-term trends. The LSTM model is trained to forecast future temperatures based on past observations, making it a useful tool for time-series prediction.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Results](#results)


## Introduction

Temperature prediction is a key task in weather forecasting. In this project, we focus on predicting the daily temperature in Seattle using historical temperature data and a **7-day moving average** feature. A **Long Short-Term Memory (LSTM)** network, which is a type of recurrent neural network (RNN), is used to handle the sequential nature of the data.

We process the dataset by:
1. Applying a 7-day moving average to smooth the temperature data.
2. Splitting the data into training and testing sets.
3. Using an LSTM model to predict future temperature values based on past observations.

The main goal is to predict future temperatures for the city of Seattle with high accuracy, utilizing the power of LSTMs for time-series forecasting.

## Features

- **7-Day Moving Average**: A feature that smooths the data by averaging the previous 7 days of temperature, helping the model to capture long-term trends.
- **LSTM Model**: A neural network architecture specialized in time-series data that helps in predicting future temperature values based on past observations.
- **Data Visualization**: Visualizations of actual vs predicted temperatures and training loss over epochs.
- **Performance Metrics**: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²) for evaluating the model's prediction accuracy.
- **Epochs** : 100 for both types of temperatures.

## Technologies Used

- **Python**: Programming language used for the entire project.
- **TensorFlow/Keras**: Framework used to build and train the LSTM model.
- **NumPy**: For numerical operations and data manipulation.
- **Matplotlib**: For visualizing training progress and results.
- **Pandas**: For data manipulation and handling time-series data.
- **Seattle Temperature Dataset**: A dataset containing historical daily temperature data for Seattle.


## Results

After training the LSTM model on the Seattle temperature dataset, the model achieved the following performance metrics for predicting the maximum and minimum temperatures:

### **For Maximum Temperature:**
- **Mean Squared Error (MSE)**: The model achieved an MSE of **3.29**.
- **Root Mean Squared Error (RMSE)**: The model obtained an RMSE of **1.81°C**.
### **For Minimum Temperature:**
- **Mean Squared Error (MSE)**: The model achieved an MSE of **3.42**.
- **Root Mean Squared Error (RMSE)**: The RMSE for minimum temperature predictions was **1.85°C**.




