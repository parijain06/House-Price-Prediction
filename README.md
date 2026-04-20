# 🏠 House Price Prediction using Machine Learning

## 📌 Introduction

This project focuses on predicting house prices using machine learning techniques. The goal is to build a regression model that can estimate the sale price of a house based on various features such as size, quality, and construction details.

---

## 📊 Dataset

The dataset used in this project is the **House Prices dataset** from Kaggle.

It contains information about different houses, including:

* Overall quality of the house
* Living area size
* Garage capacity
* Basement area
* Number of bathrooms
* Year of construction

The target variable is:

* **SalePrice** → the price of the house

---

## 🧹 Data Preprocessing

The dataset was cleaned and prepared before training the model:

* Selected relevant numerical features
* Handled missing values using median imputation
* Removed unnecessary columns
* Ensured all features were in numeric format

---

## ⚙️ Feature Selection

The following features were used for prediction:

* OverallQual
* GrLivArea
* GarageCars
* TotalBsmtSF
* FullBath
* YearBuilt

These features were chosen because they have a strong influence on house prices.

---

## 🤖 Model Training

Two machine learning models were used:

1. **Linear Regression**

   * A basic model to understand relationships between features and price

2. **Random Forest Regressor**

   * A more advanced model that improves prediction accuracy

---

## 🔧 Parameter Tuning

To improve performance, hyperparameter tuning was performed using GridSearchCV.

Parameters tuned:

* Number of trees (n_estimators)
* Maximum depth of trees (max_depth)
* Minimum samples split (min_samples_split)

This helped in selecting the best model configuration.

---

## 📈 Performance Evaluation

The models were evaluated using the following metrics:

* **MAE (Mean Absolute Error)** → average prediction error
* **MSE (Mean Squared Error)** → squared error measure
* **RMSE (Root Mean Squared Error)** → error in price units
* **R² Score** → model accuracy

The tuned Random Forest model showed better performance compared to Linear Regression.

---

## 📊 Visualization

A scatter plot of actual vs predicted prices was used to visualize model performance.

---

## ✅ Conclusion

The project successfully predicts house prices using machine learning techniques.

Key insights:

* House quality and living area are major factors influencing price
* Random Forest performs better than Linear Regression
* Parameter tuning significantly improves model accuracy

---

## 🚀 Future Improvements

* Use more features for better accuracy
* Apply advanced models like XGBoost
* Perform deeper feature engineering
* Handle categorical variables more effectively

---

## 👩‍💻 Author

Pari Jain
