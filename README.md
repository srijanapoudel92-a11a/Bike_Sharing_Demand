#Bike Sharing Demand Prediction

# Project Overview

This project predicts the **number of bikes rented** using the Bike Sharing Demand dataset from Kaggle. It uses factors like time, weather, temperature, humidity, and working days.

# Dataset

The dataset contains information about **datetime, season, holiday, working day, weather, temperature, humidity, windspeed, and bike count**.

# What I Did

* Checked and cleaned the data
* Removed duplicate records
* Performed EDA using different graphs
* Created useful time-based features from `datetime`
* Used One-Hot Encoding for categorical data
* Used StandardScaler where needed
* Trained Linear Regression and Random Forest models
* Used TimeSeriesSplit for validation
* Compared the models using MAE, RMSE, and R²

# Results

The analysis showed that **time, season, weather, and temperature** affect bike rental demand. The two models were compared, and the better-performing model was selected as the final model.

# Model and GUI

The final model was saved as **`bike_demand_model.pkl`**. A simple **Gradio GUI** was created where users can enter the required information and get the predicted number of bike rentals.

# Conclusion

This project helped me understand the complete machine-learning process from **data cleaning and analysis to model training, evaluation, saving, and prediction**.
