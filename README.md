# ANN Regression Model for Combined Cycle Power Plant Energy
Overview

This project implements an Artificial Neural Network (ANN) regression model to predict the electrical energy output of a Combined Cycle Power Plant (CCPP). The model leverages environmental and operational data to provide accurate energy forecasting, supporting better planning and efficiency analysis.

Dataset

The project uses the Folds5x2_pp.csv dataset, which contains operational records from a Combined Cycle Power Plant. Each entry consists of the following input features:

Temperature (°C)

Ambient Pressure (mbar)

Relative Humidity (%)

Exhaust Vacuum (cm Hg)

The target variable is the electrical energy output (MW).

Methodology

Data Preprocessing – Load and clean the dataset, handle missing values, and normalize/scale features for optimal ANN training.

Model Building – Develop a multi-layer ANN regression model using frameworks like TensorFlow or Keras.

Training and Validation – Split the data into training and testing sets to evaluate model performance.

Evaluation Metrics – Assess the model using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.

Results

The ANN model predicts the energy output based on the four input features (temperature, pressure, humidity, and vacuum). Visualizations such as loss curves and predicted vs. actual plots can be included to illustrate model performance.

