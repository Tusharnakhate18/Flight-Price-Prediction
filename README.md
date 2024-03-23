# Flight Price Prediction Project
## Overview:
This project aims to predict the prices of flight tickets using machine learning techniques. It involves exploratory data analysis (EDA), feature engineering, model building, and evaluation.

## Dataset:
The dataset used for this project consists of historical flight data, including various features such as airline, source, destination, departure time, arrival time, duration, number of stops, etc. It is split into training and test sets.

## Contents:
- Flight_Price_Prediction.ipynb: Jupyter Notebook containing the Python code for data preprocessing, exploratory data analysis, feature engineering, model building, and evaluation.
- Data_Train.xlsx: Excel file containing the training dataset.
- Test_set.xlsx: Excel file containing the test dataset.
- README.md: This file, providing an overview of the project.

## Data Preprocessing:
- Imported necessary libraries: pandas, numpy, matplotlib, seaborn.
- Loaded the training and test datasets.
- Concatenated the datasets for preprocessing.
## Exploratory Data Analysis (EDA):
Explored the data using various visualizations to understand the distributions and relationships between features.

## Feature Engineering:
- Extracted features such as date, month, year from the 'Date_of_Journey' column.
- Processed arrival and departure times to extract hour and minute features.
- Encoded categorical variables using label encoding and one-hot encoding.
  
## Model Building:
- Trained machine learning models such as Random Forest, Gradient Boosting, etc., to predict flight prices.
- Evaluated model performance using metrics such as RMSE, MAE, etc.

## Conclusion:
This project demonstrates the process of predicting flight prices using machine learning techniques. Further improvements can be made by fine-tuning hyperparameters, trying different algorithms, and incorporating additional features.

