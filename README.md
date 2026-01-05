# 🚗 Vehicle Fuel Efficiency Prediction

## Overview
This project builds an end-to-end machine learning and deep learning pipeline to predict vehicle fuel efficiency (MPG) using structured automotive data.

## Problem Statement
Fuel efficiency prediction helps manufacturers and analysts understand the impact of vehicle design parameters such as weight, engine displacement, and horsepower on fuel consumption.

## Dataset
- Source: UCI Auto MPG Dataset (via Kaggle)
- Size: ~400 samples
- Features: Cylinders, displacement, horsepower, weight, acceleration, model year, origin

## Approach
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature engineering and encoding
- Baseline model: Random Forest Regressor
- Deep learning model: Fully connected neural network (TensorFlow/Keras)
- Model evaluation using MAE and MSE
- Regression diagnostics using residual analysis

## Results
- Deep learning model achieved lower MAE compared to baseline model
- Residual analysis indicates good generalization with no major bias

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib, Seaborn

## How to Run
```bash
pip install -r requirements.txt
python main.py
