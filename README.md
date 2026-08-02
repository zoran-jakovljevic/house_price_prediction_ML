# 🏠 California Housing Price Prediction

Machine Learning project for predicting California housing prices using multiple regression algorithms and comparing their performance.

---

## 📌 Project Overview

The goal of this project is to predict the median house value using demographic and geographic information from the California Housing dataset.

The project covers the complete Machine Learning workflow:

- Data loading
- Exploratory Data Analysis (EDA)
- Missing value handling
- One-Hot Encoding
- Feature Engineering
- Log Transformation
- Correlation Analysis
- Train/Test Split
- Feature Scaling
- Model Training
- Model Evaluation
- Hyperparameter Tuning
- Feature Importance Analysis

---

## 📂 Dataset

California Housing Dataset

Target variable:

- `median_house_value`

Main features include:

- Longitude
- Latitude
- Median Income
- Population
- Households
- Total Rooms
- Total Bedrooms
- Housing Median Age
- Ocean Proximity

---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied:

- Missing values imputed using median
- One-Hot Encoding for categorical variables
- Feature engineering:
  - Rooms per household
  - Bedrooms per room
  - Population per household
- Log transformation of engineered features
- Correlation analysis
- Standardization using StandardScaler (Linear Regression only)

---

## 🤖 Models Used

The following regression algorithms were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

---

## 📊 Evaluation Metrics

The models were evaluated using:

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

## 🔧 Hyperparameter Tuning

The best-performing model (XGBoost) was further optimized using:

- RandomizedSearchCV
- 5-Fold Cross Validation

Optimized parameters:

- n_estimators
- max_depth
- learning_rate

---

## 📈 Feature Importance

Feature importance analysis was performed using the optimized XGBoost model to identify the variables with the greatest influence on house price prediction.

---

## 🛠 Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost

---

## 🚀 Results

Among all tested models, **XGBoost achieved the best predictive performance**.

Hyperparameter tuning using RandomizedSearchCV further improved the model performance.

---
