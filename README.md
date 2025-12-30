# Shale Well EUR Prediction Model
## Overview

This project implements a Multiple Linear Regression model to predict the Estimated Ultimate Recovery (EUR) of a shale gas well based on geological and operational parameters.

The model is trained on historical shale well data, scaled appropriately, and deployed using a simple Flask web application that allows users to input well parameters and obtain EUR predictions.

## Objective

Predict EUR (Estimated Ultimate Recovery) accurately

Apply machine learning regression techniques

Demonstrate end-to-end ML workflow:

Data preprocessing

Model training

Model serialization

Web-based deployment

## Methodology

Data Preprocessing

Cleaning missing or inconsistent values

Feature scaling using StandardScaler

Model Selection

Multiple Linear Regression

Chosen for interpretability and baseline performance

Model Training

Performed in correctedmodel.ipynb

Evaluated using regression metrics (R², error analysis)

Model Deployment

Trained model saved as .pkl

Flask app loads model & scaler

User inputs → scaled → predicted EUR

## Technologies Used

Python

Pandas & NumPy

Scikit-learn

Flask

HTML (Frontend)

## How to Run the Project
1️⃣ Install Dependencies
pip install numpy pandas scikit-learn flask

2️⃣ Run the Application
python app.py

3️⃣ Open in Browser
http://127.0.0.1:5000/

## Input & Output

Input:

Geological parameters

Well completion variables

Output:

Predicted Estimated Ultimate Recovery (EUR)

## Use Cases

Shale gas production forecasting

Decision support for drilling investments

Educational project for applied machine learning

## Future Improvements

Replace linear regression with Random Forest / XGBoost

Add feature importance visualization

Improve UI with validation and charts

Deploy on cloud (Heroku / Render)

## License

This project is for educational and research purposes.
