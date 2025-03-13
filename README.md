# New-York-City-Taxi-trip-duration
Advanced Machine Learning - Final Project

## Introduction:
This project focuses on predicting the duration of taxi trips in New York City using machine learning and deep learning models. The goal is to compare the performance of neural networks and XGBoost regressors in estimating trip duration based on features such as location, time, and passenger count.

## Methods:
- Data Preparation: The dataset was cleaned, missing values handled, and outliers removed. Feature engineering included distance calculation, direction bearing, and categorical encoding.
- Modeling:
Neural Networks: Four architectures were tested using TensorFlow, with varying complexity and activation functions (ReLU, Tanh). Training included techniques like ReduceLROnPlateau and EarlyStopping.
XGBoost: Three models were trained with different hyperparameter tuning strategies, leveraging subsampling and feature selection.
- Explainability: LIME was used to analyze feature importance in neural networks, while XGBoost’s built-in feature importance was also examined.
- Evaluation Metrics: Models were assessed using Mean Absolute Error (MAE) and Root Mean Squared Logarithmic Error (RMSLE).

## Results & Conclusions:
XGBoost outperformed neural networks, achieving the lowest MAE and RMSLE.
Feature engineering was crucial, with variables like distance, latitude, and longitude significantly influencing predictions.
Future improvements may include incorporating external factors like weather and traffic data for better accuracy.
Neural networks, while competitive, were less interpretable and computationally expensive, making XGBoost a more suitable choice for structured tabular data.
This project demonstrates the power of XGBoost for predictive modeling on structured datasets while highlighting areas for further enhancement.
