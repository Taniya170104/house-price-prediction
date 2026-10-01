# House Price Prediction

A data analytics and machine learning project focused on predicting house prices through data preprocessing, feature engineering, and regression techniques.

## Project Overview

This project uses a housing dataset to develop a machine learning model for predicting house sale prices. The project focuses on preparing structured data, handling missing values, encoding categorical features, and applying a regression model for price prediction.

## Objectives

- Clean and preprocess the housing dataset
- Handle missing values and irrelevant features
- Convert categorical variables into numerical features
- Prepare the dataset for machine learning
- Build a regression model to predict house prices
- Generate predictions for the test dataset

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Data Preprocessing

The project includes:

- Missing-value treatment using mean and mode imputation
- Removal of features with excessive missing values
- Categorical variable encoding
- Feature preparation for model training

## Machine Learning Model

The project uses **HistGradientBoostingRegressor** for house price prediction.

The model is trained on the processed housing data and used to generate predicted sale prices for the test dataset.


## Project Structure

```text
house-price-prediction/
├── README.md
└── House_price_prediction.ipynb
```

## Results

The trained model generates predicted house prices for the test dataset, which are exported for further analysis and evaluation.
