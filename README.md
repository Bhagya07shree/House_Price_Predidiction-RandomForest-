House Price Prediction Using Random Forest
**📌 Project Overview**
This project aims to predict house prices using machine learning techniques. The Random Forest algorithm is used to achieve high accuracy in price estimation.

**📊  Dataset**
The dataset contains house features like area (sq ft), location, building type, and exterior type.
The target variable is the house price.
Missing values have been handled using data imputation technique

**🔧 Feature Engineering & Preprocessing**
Handled missing values for categorical and numerical features.
Converted categorical variables into numeric using one-hot encoding.
Removed outliers and normalized the data.


**📈 Model Training & Evaluation**
We tested multiple models, and the Random Forest model performed the best:

Model	               MSE	         MAE	      R² Score
Linear Regression	   3.35e+09	     37887.87	  0.531
Random Forest	       2.88e+08	     7964.91	  0.96
✅ Random Forest is the best model with an R² score of 0.96, indicating high accuracy.

**📌 Results**
Here is a sample comparison of actual vs. predicted house prices:
Area (Sq Ft)	Actual Price	Predicted Price
12205       	187500	       182403.10
9416	        311872	       336905.99
23595	        260000	       225927.14
