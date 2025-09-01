# 🚗 Fuel Efficiency Prediction using Machine Learning

This project predicts vehicle fuel efficiency (measured in MPG) using the Auto MPG dataset. It demonstrates an end-to-end machine learning workflow — from data cleaning and EDA to model building, evaluation, and comparison — using industry-standard tools like pandas, scikit-learn, and seaborn.

---

## 📁 Dataset
- **Source:** [UCI Auto MPG Dataset](https://archive.ics.uci.edu/ml/datasets/auto+mpg)
- **Target:** `mpg` (miles per gallon)
- **Features:** `cylinders`, `displacement`, `horsepower`, `weight`, `acceleration`, `model year`, `origin`

---

## 🛠 Technologies Used
- Python (pandas, numpy)
- Data visualization: seaborn, matplotlib
- Modeling: scikit-learn
- Jupyter Notebook

---

## 📊 Techniques Implemented
- Data Cleaning (handling missing values, converting data types)
- Outlier Detection and Removal (IQR method)
- Feature Scaling (StandardScaler, MinMaxScaler)
- Encoding categorical features (`origin`)
- Model Training:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - Random Forest Regressor
- Hyperparameter Tuning with GridSearchCV
- K-Fold Cross-Validation
- Evaluation using:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score

---

## 🧠 Key Results
| Model                | RMSE   | R² Score |
|---------------------|--------|----------|
| Linear Regression    | ~3.2   | ~0.79    |
| Ridge Regression     | ~3.1   | ~0.80    |
| Lasso Regression     | ~3.4   | ~0.76    |
| Random Forest        | ~2.5   | ~0.89    |

> 📌 *Random Forest with tuned hyperparameters performed the best.*
