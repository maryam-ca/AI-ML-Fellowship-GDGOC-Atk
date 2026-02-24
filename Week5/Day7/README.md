# Week 5 — Machine Learning Implementation

## 📌 Overview

This project covers the basic concepts of Machine Learning and the implementation of Linear Regression. The main objective of this task is to understand how machine learning models work internally by implementing algorithms from scratch instead of only using built-in library functions.

This notebook includes both theoretical explanations and practical implementations.

---

## 🧠 Introduction to Machine Learning

Machine Learning is a branch of Artificial Intelligence that enables computers to learn patterns from data without being explicitly programmed. Instead of writing rules manually, we provide data to the machine and it automatically learns relationships.

### Types of Machine Learning

#### 1. Supervised Learning
Uses labeled data to train models.  
Example: Predicting house prices.

#### 2. Unsupervised Learning
Uses unlabeled data to find hidden patterns.  
Example: Customer segmentation.

#### 3. Reinforcement Learning
Learns through rewards and penalties.  
Example: Game-playing AI systems.

---

## 📈 Linear Regression

Linear Regression is a supervised learning algorithm used to predict continuous values. It finds the best-fit straight line between input and output variables.

### Equation

Y = mX + b

Where:
- **m** = slope of the line
- **b** = intercept
- **X** = input feature
- **Y** = predicted output

---

## ⚙️ Linear Regression Implementation (From Scratch)

In this section, Linear Regression is implemented manually using mathematical formulas.

Steps included:

- Creating sample dataset
- Calculating mean values
- Computing slope using covariance and variance
- Finding intercept
- Generating predictions
- Plotting regression line

This implementation helps understand how Linear Regression works internally without using built-in functions.

---

## 🔁 Gradient Descent Implementation

Gradient Descent is an optimization algorithm used to minimize the error in machine learning models.

In this notebook, Gradient Descent is implemented step by step:

- Initialize slope and intercept
- Set learning rate
- Calculate prediction error
- Compute gradients
- Update weights iteratively
- Repeat for multiple epochs

This process allows the model to gradually learn the best-fit line.

---

## 🤖 Linear Regression Using Scikit-Learn

After implementing the algorithm from scratch, the same Linear Regression model is implemented using the Scikit-Learn library to compare results.

Steps included:

- Importing LinearRegression module
- Reshaping data
- Training the model using `.fit()`
- Making predictions
- Plotting regression line

---

## 🎯 Learning Outcomes

By completing this project, the following concepts were learned:

- Basic understanding of Machine Learning
- Working of Linear Regression algorithm
- Mathematical computation of slope and intercept
- Implementation of Gradient Descent
- Difference between manual implementation and library usage

---

## 📂 Project Structure


Week5/
│── Week5_Machine_Learning.ipynb
│── README.md


---

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Run all cells sequentially.
3. Observe output graphs and results.

---

## ✅ Conclusion

This project successfully demonstrates the fundamentals of Machine Learning and provides a clear understanding of Linear Regression through both manual implementation and library-based methods. Implementing Gradient Descent from scratch helped in understanding how models learn step by step.

---