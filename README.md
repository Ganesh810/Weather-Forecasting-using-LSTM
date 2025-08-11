# Weather-Forecasting-using-LSTM
Weather Prediction using Machine Learning
Overview
This project predicts weather conditions using historical weather data and machine learning models. The dataset (weatherHistory.csv) contains various weather attributes such as temperature, humidity, wind speed, and visibility. The goal is to forecast temperature trends and general weather conditions.

Dataset
File: weatherHistory.csv

Key Features:

Formatted Date – Timestamp of the weather record

Summary – Short description of weather

Precip Type – Type of precipitation (rain/snow)

Temperature (C) – Recorded temperature in Celsius

Apparent Temperature (C) – Feels-like temperature

Humidity, Wind Speed (km/h), Visibility (km)

Pressure (millibars)

Technologies Used
Python 3.x

Jupyter Notebook

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, joblib

Workflow
Data Loading & Cleaning:

Handle missing values

Convert date/time formats

Encode categorical variables

Exploratory Data Analysis:

Visualize temperature trends

Analyze humidity and precipitation patterns

Feature Engineering:

Extract date and time-based features

One-hot encode categorical features

Model Building:

Train-Test Split

Apply regression models such as Linear Regression and Random Forest

Evaluate with RMSE, MAE, and R² score

Prediction & Saving Model:

Predict temperature for test data

Save trained model for deployment

Results
Accurate temperature predictions

Clear understanding of factors influencing temperature
