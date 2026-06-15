# Task 2: Model Comparison Using California Housing Dataset

## Summerix Global AI/ML Internship

### Intern Details

* **Name:** Yash Kunjir
* **Domain:** Artificial Intelligence and Machine Learning
* **Duration:** 4 Weeks
* **Batch Start Date:** 25 May

---

## Project Overview

This project focuses on comparing multiple machine learning regression models for house price prediction using the California Housing Dataset.

The objective is to apply feature engineering techniques, perform feature scaling, train multiple regression models, evaluate their performance, and identify the best-performing model based on evaluation metrics.

---

## Dataset Information

The California Housing Dataset contains information about housing districts in California, including:

* Longitude
* Latitude
* Housing Median Age
* Total Rooms
* Total Bedrooms
* Population
* Households
* Median Income
* Ocean Proximity

### Target Variable

* **Median House Value**

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Machine Learning Models Used

### 1. Linear Regression

A statistical model that establishes a linear relationship between independent and dependent variables.

### 2. Ridge Regression

An improved version of Linear Regression that uses regularization to reduce overfitting and improve generalization.

### 3. Decision Tree Regressor

A tree-based machine learning algorithm capable of capturing non-linear relationships within data.

---

## Feature Engineering

The following preprocessing steps were performed:

* Data Cleaning
* Handling Missing Values
* Feature Scaling using StandardScaler
* Train-Test Split

Feature scaling was applied to ensure all features contribute equally during model training.

---

## Model Evaluation Metrics

The models were evaluated using:

### RMSE (Root Mean Squared Error)

Measures prediction error.

### R² Score

Measures how well the model explains the variance in the target variable.

---

## Model Performance Results

| Model                   | RMSE     | R² Score |
| ----------------------- | -------- | -------- |
| Ridge Regression        | 70057.42 | 0.6255   |
| Linear Regression       | 70060.52 | 0.6254   |
| Decision Tree Regressor | 71510.90 | 0.6098   |

---

## Best Model

### Ridge Regression

Ridge Regression achieved:

* Lowest RMSE
* Highest R² Score
* Better generalization performance
* Reduced risk of overfitting

Therefore, Ridge Regression was selected as the best-performing model.

---

## Visualizations Included

* Correlation Heatmap
* House Price Distribution Histogram
* Model Comparison Bar Chart
* Actual vs Predicted Graph

---

## Conclusion

This project demonstrated the complete machine learning workflow, including data preprocessing, feature scaling, model training, model comparison, and performance evaluation.

Among the evaluated algorithms, Ridge Regression achieved the best performance and was selected as the final model for house price prediction.

The project provided practical experience in feature engineering, model optimization, performance evaluation, and model selection.

---

## GitHub Repository

https://github.com/yashkunjir2006-commits/summerix-global-ai-ml-internship-yash-kunjir
