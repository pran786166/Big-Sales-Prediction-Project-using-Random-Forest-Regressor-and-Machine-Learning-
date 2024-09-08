# Big-Sales-Prediction-Project-using-Random-Forest-Regressor-and-Machine-Learning-
This project uses a **Random Forest Regressor** to predict sales based on a dataset containing 12 variables. The main objective is to build a predictive model for sales performance.

## Dataset Overview

The dataset contains the following 12 variables:

1. Item_Identifier
2. Item_Weight
3. Item_Fat_Content
4. Item_Visibility
5. Item_Type
6. Item_MRP
7. Outlet_Identifier
8. Outlet_Establishment_Year
9. Outlet_Size
10. Outlet_Location_Type
11. Outlet_Type
12. Item_Outlet_Sales

## Libraries Used

   import pandas as pd
   import numpy as np
   import seaborn as sns

## Data Used :
   https://github.com/YBI-Foundation/Dataset/raw/main/Big%20Sales%20Data.csv

##Exploratory Data Analysis (EDA)
   First 5 Rows: To display the first 5 rows of the dataset:
   Data Information: To understand the structure of the dataset:
   Summary Statistics: For an overview of the dataset's statistical properties:
   Handling Missing Values: Missing values in the Item_Weight column are replaced with the mean based on the Item_Type:

## Feature Engineering
   Categorical features like Item_Fat_Content, Item_Type, Outlet_Size, Outlet_Location_Type, and Outlet_Type are converted to numerical categories using df.replace().

   Example for Item_Fat_Content: Item_Fat_Content

## Data Preprocessing
   Null values are filled.

## Categorical features are converted into numerical values for modeling.

## Model Development
   The target variable (y) and feature variables (X) are defined as follows:

## Random Forest Regressor
   The Random Forest Regressor is used for prediction:

## Model Evaluation
   Evaluate the model performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), or R-Squared score.

## Conclusion
  The Random Forest model successfully predicts sales based on the available features, with scope for further optimization and feature engineering.

## Future Work
   Hyperparameter tuning for better performance.
   Implementing other machine learning models for comparison.
