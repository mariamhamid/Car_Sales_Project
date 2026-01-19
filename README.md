# 🚗 Car Sales Price Regression
## Project Overview
This project focuses on predicting car prices using regression models based on car attributes such as make, colour, mileage, and number of doors.
The goal is to compare different regression algorithms and understand how data quality and feature engineering affect model performance.

---
## Dataset
---
The dataset contains 1000 car records with the following features:

Make (categorical)

Colour (categorical)

Odometer (KM) (numerical)

Doors (numerical)

Price (target variable)

Missing values were handled during preprocessing.

---
## Problem Type

Supervised Learning

Regression

---
## Preprocessing

Removed rows with missing target values (Price)

Handled missing values using SimpleImputer

Encoded categorical features using OneHotEncoder

Applied different preprocessing steps using ColumnTransformer

Combined preprocessing and models using Pipeline

---

## Models Used

Ridge Regression

Support Vector Regression (Linear)

Support Vector Regression (RBF)

Random Forest Regressor

---

## Evaluation Metric

R² Score (Coefficient of Determination)

---

## Results Summary

Ridge Regression achieved the best performance

Random Forest performed similarly but slightly lower

SVR models performed poorly, especially with the RBF kernel

Overall R² scores were low, indicating feature limitations rather than model issues

---

## Key Takeaways

Model performance is strongly affected by feature quality

Linear models worked better than complex non-linear ones for this dataset

Feature engineering would likely improve results more than changing models

---

## Technologies Used

Python

pandas, NumPy

scikit-learn

Jupyter Notebook

---

## Future Improvements

Add more informative features (car year, engine size, condition)

Perform deeper hyperparameter tuning

Try advanced feature engineering

Increase dataset size
