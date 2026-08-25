## House Price Prediction

Project Overview

This project focuses on predicting house prices using Machine Learning regression techniques.

The model learns from historical housing data and uses different property features to estimate the expected price of a house. The project covers the complete Machine Learning workflow, starting from data exploration and preprocessing to model training, evaluation, and testing on new data.

---

## Project Objective

The main objective of this project is to build a Machine Learning model that can predict house prices as accurately as possible based on the available housing features.

The project also compares model performance using different regression evaluation metrics.

---

## Dataset

The dataset contains information about houses and their related features, which are used to predict the target variable:

**Target Variable:** House Price

The data is explored and prepared before being passed to the Machine Learning models.

---

## Machine Learning Workflow

The project follows these main steps:

### 1. Data Loading

The housing dataset is loaded using Pandas and inspected to understand its structure.

### 2. Data Exploration

The dataset is analyzed to identify:

* Number of rows and columns
* Data types
* Statistical information
* Relationships between features
* Missing values
* Duplicate records

### 3. Data Preprocessing

The data is cleaned and prepared for Machine Learning by:

* Handling missing values
* Detecting and handling outliers
* Removing duplicate records
* Preparing numerical and categorical features
* Applying the required transformations

### 4. Feature Preprocessing

The features are transformed and scaled when necessary so that they can be used effectively by the Machine Learning models.

### 5. Model Training

Different regression models are trained using the prepared dataset.

The project includes models such as:

* Linear Regression
* Random Forest Regressor

### 6. Model Evaluation

The trained models are evaluated using several regression metrics:

* **MAE:** Mean Absolute Error
* **MSE:** Mean Squared Error
* **RMSE:** Root Mean Squared Error
* **R² Score:** Coefficient of Determination

These metrics help measure how accurately the models predict house prices.

### 7. Model Testing and Prediction

After training and evaluation, the selected model is tested on new input data to generate a predicted house price.

The prediction stage demonstrates how the trained Machine Learning model can be used to estimate the price of a previously unseen house.

---

## Models Used

### Linear Regression

A basic regression algorithm used as a baseline model for predicting continuous house prices.

### Random Forest Regressor

An ensemble Machine Learning algorithm that combines multiple decision trees to improve prediction performance and handle complex relationships between features.

---

## Model Evaluation

The models are compared based on their:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

A lower MAE, MSE, and RMSE indicate smaller prediction errors, while a higher R² score indicates that the model explains a larger proportion of the variation in house prices.

---

## Project Structure

```text
House-Price-Prediction/
│
├── notebooks/
│   ├── preparedataset.ipynb
│   ├── trainmodel.ipynb
│   ├── evaluatemodel.ipynb
│   └── finaltestmodel.ipynb
│
├── models/
│   ├── random_forest_model.pkl
│   ├── preprocessor.pkl
│   └── scaler.pkl
│
├── README.md
└── requirements.txt
```

---

## Technologies & Libraries

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

## Saved Models

The trained model and preprocessing components are saved using Joblib so they can be reused later without retraining the entire model.

Saved files include:

* `random_forest_model.pkl`
* `preprocessor.pkl`
* `scaler.pkl`

---

##  Project Outcome

The final result is a complete Machine Learning pipeline capable of:

**Housing Data → Data Cleaning → Preprocessing → Model Training → Model Evaluation → House Price Prediction**

This project demonstrates the practical application of Machine Learning for a regression problem and shows the complete process of building, evaluating, and using a predictive model.

---

## Authors

1- Shahd Anwar

2- Shireen Elsayed 

3- Salma Eslam

Faculty of Computers and Artificial Intelligence
