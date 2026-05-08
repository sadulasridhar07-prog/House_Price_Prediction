# House Price Prediction

## Project Overview
This project focuses on predicting house prices using Machine Learning regression algorithms. The dataset contains various house features, and the objective is to build an accurate regression model for price prediction.

---

## Objective
Build a regression model to predict house prices using feature engineering, preprocessing, and model evaluation techniques.

---

## Dataset
Dataset used from Kaggle:

House Price Prediction Dataset

Features include:
- Area
- Bedrooms
- Bathrooms
- Stories
- Parking
- Furnishing Status
- Main Road Access
- Air Conditioning
- Preferred Area
- Price

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## Machine Learning Models Used
1. Linear Regression
2. Random Forest Regressor
3. Gradient Boosting Regressor

---

## Project Workflow

### 1. Data Preprocessing
- Loaded dataset
- Checked missing values
- Handled null values
- Converted categorical data into numerical format
- Applied feature scaling

### 2. Exploratory Data Analysis (EDA)
- Correlation heatmap
- Distribution plots
- Feature relationship analysis

### 3. Feature Engineering
- Encoding categorical variables
- Log transformation
- Data scaling

### 4. Model Training
Trained and compared:
- Linear Regression
- Random Forest
- Gradient Boosting

### 5. Model Evaluation
Evaluation metrics used:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- Residual Analysis

---

## Best Model
The best-performing model was selected based on the lowest RMSE value.

---

## Files Included

```text
house_price_prediction.ipynb
house_price_model.pkl
predict.py
README.md
Housing.csv
