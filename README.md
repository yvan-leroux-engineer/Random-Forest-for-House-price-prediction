# Real Estate Price Prediction using RandomForest Regressor

Welcome to the repository for the "Real Estate Price Prediction" project. This project focuses on creating a predictive model for apartment prices based on various parameters derived from financial transactions data. The model leverages the RandomForest Regressor algorithm.

## Objective
The main objective of this project is to build a predictive model for apartment prices using features such as commune, surface area, number of rooms, and year of transaction.

## Data Preprocessing
The project starts with cleaning and preparing the data:
- Data is loaded from CSV files and necessary columns are selected.
- Columns with mixed types are handled.
- Null values are filled, and data is converted to appropriate data types.

## Dataset Preparation
The dataset is processed further for analysis:
- Columns are encoded using LabelEncoder for categorical features.
- The dataset is split into features (`dataX`) and target (`dataY`) variables.

## Model Training
A RandomForest Regressor model is trained on the data:
- The data is split into training, validation, and test sets.
- RandomForest Regressor is configured with hyperparameters.
- The model is trained and evaluated on validation and test sets.

## Evaluation
The model's performance is evaluated:
- R² scores are calculated for the validation and test sets.

## Predictions
Predictions are made using the trained model:
- New data for prediction is prepared.
- The trained model is used to predict prices based on the new data.

---
Project by Yvan Leroux
