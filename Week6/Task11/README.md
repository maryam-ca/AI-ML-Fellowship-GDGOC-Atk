# Housing Price Prediction using Machine Learning

## Project Overview

This project focuses on predicting housing prices using multiple Machine Learning models. 
The objective is to compare different algorithms and analyze their performance in terms of accuracy and error.

We implemented Linear Regression as a baseline model and compared it with advanced ML models including tree-based models, kernel-based models, and ensemble learning techniques.

---

## Dataset

We used the California Housing dataset available in Scikit-learn.

The dataset contains various features such as:
- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

The target variable is the median house value.

---

## Machine Learning Models Implemented

### 1. Linear Regression
Used as a baseline model.
It assumes a linear relationship between input features and target variable.

### 2. Decision Tree Regressor
A tree-based model that splits the dataset into branches based on feature importance.
It can capture non-linear relationships.

### 3. Random Forest Regressor
An ensemble method that builds multiple decision trees and averages their predictions.
It reduces overfitting and improves accuracy.

### 4. Support Vector Regressor (SVR)
A kernel-based model that finds the best boundary with maximum margin.
Feature scaling was applied before training.

### 5. AdaBoost Regressor
A boosting algorithm that combines weak learners sequentially.
Each new model focuses on correcting previous errors.

### 6. Gradient Boosting Regressor
An advanced boosting algorithm that builds models sequentially
and minimizes error using gradient descent.

---

## Data Preprocessing

The dataset was split into training and testing sets using an 80-20 ratio.

StandardScaler was applied for feature scaling, especially for models like SVR which are sensitive to feature magnitude.

---

## Hyperparameter Tuning

GridSearchCV was used to tune Random Forest parameters such as:
- n_estimators
- max_depth

This helped in selecting the best performing model configuration.

---

## Model Evaluation Metrics

We evaluated models using:

- R2 Score (Coefficient of Determination)
- Mean Squared Error (MSE)

Higher R2 Score indicates better prediction performance.
Lower MSE indicates lower prediction error.

---

## Model Comparison

After training all models, we compared their performance.

Tree-based and Boosting models performed better than Linear Regression
because they can capture complex non-linear patterns in the data.

Random Forest and Gradient Boosting achieved the highest accuracy.

---

## Conclusion

This project demonstrates that advanced ensemble models outperform basic linear models for complex datasets.

While Linear Regression is simple and fast, it cannot capture complex patterns.
Tree-based and boosting models provide better accuracy and generalization.

Ensemble learning techniques like Random Forest and Gradient Boosting are more powerful for real-world regression problems such as housing price prediction.

---

## Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Submission Details

This repository contains:

- One Jupyter Notebook (.ipynb)
- This README file

All models, explanations, comparisons, and visualizations are included inside the single notebook file as required.

---

## Author

Maryam Fatima
