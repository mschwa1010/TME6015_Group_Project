# TME6015 Project: Taxi Demand Prediction in Chicago

This repository contains the solution for the TME6015 course project, which involves the development and deployment of machine learning models for predicting taxi demand in Chicago. The project includes three main Jupyter notebooks focusing on data preparation, feature engineering, and predictive analytics, each of which plays a critical role in building an accurate and reliable model.

## Project Overview

### Problem Statement
This project tackles the machine learning problem of forecasting taxi trip demand in Chicago. Using historical 2013 taxi data from the Chicago Data Portal, we aim to accurately predict the number of taxi trips across various temporal granularities (hourly, two-hourly, six-hourly, and daily). We enriched the data with spatial Points of Interest (POIs), local event information, and financial metrics to capture a wide array of factors that influence demand.

## Notebooks

1. **Data Preparation (`TME6015_Data_Preparation.ipynb`)**
   - Contains steps for cleaning and preprocessing the original dataset, reducing its size while retaining essential information.
   - Handles missing data and outliers to ensure data quality for training.

2. **Feature Engineering (`TME6015_Feature_Engineering.ipynb`)**
   - Enriches the dataset by adding contextual features such as POIs, event data, and temporal cycles.
   - Selects spatio-temporal variables at census tract and hourly/daily levels to capture demand patterns.

3. **Predictive Analytics (`TME6015_Predictive_Analytics.ipynb`)**
   - Implements a fully connected neural network for regression-based prediction of taxi demand.
   - Includes model training and hyperparameter tuning for each time interval (hourly, two-hourly, six-hourly, and daily).
   - The models are evaluated using R² scores, with an aim to maximize predictive accuracy.

## Model Deployment

An interactive web interface for model prediction is available at the following link:

[Predict Taxi Demand](https://tmeaiwebpage-production.up.railway.app/predict)

Username: TME6015
Password: TMEpassword

This interface allows users to input data and receive real-time predictions based on the trained models.


## Dataset Access

To run the notebooks and train the models, you will need to download the required datasets. The preprocessed and enriched datasets are too large to be uploaded to GitHub, so they have been made available through Google Drive. You can access them using the link below:

**[Download Datasets](https://drive.google.com/drive/folders/1s7ZKSe11z12nlDrVZH8a4_dNTTMYUhoH?usp=sharing)**

Ensure the datasets are placed in the appropriate directories as specified in each notebook to avoid errors during execution.


