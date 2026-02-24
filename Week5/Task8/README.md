# Logistic Regression Implementation (From Scratch + Scikit-Learn)

## 📌 Project Overview

This project implements **Logistic Regression** for binary classification.

The main objective of this task is to:

- Understand the mathematical foundation of Logistic Regression
- Implement the algorithm completely from scratch
- Compare results with Scikit-Learn implementation
- Visualize the learning process using graphs

This project was completed as part of the **Week 5 Fellowship Assignment**.

---

## 🎯 Project Objectives

- Understand the working of Logistic Regression
- Implement the Sigmoid function manually
- Implement Binary Cross Entropy loss
- Implement Gradient Descent optimization
- Train and evaluate the model
- Compare results with Scikit-Learn
- Visualize performance using graphs

---

## 📚 What is Logistic Regression?

Logistic Regression is a **Supervised Machine Learning Algorithm** used for **classification problems**.

Unlike Linear Regression (which predicts continuous values), Logistic Regression predicts **probability values between 0 and 1**.

If probability ≥ 0.5 → Class 1  
If probability < 0.5 → Class 0  

It is commonly used for:

- Spam Detection
- Disease Prediction
- Fraud Detection
- Binary Classification Tasks

---

## 🧠 Mathematical Background

### 1️⃣ Hypothesis Function

The linear equation used is:

z = wX + b  

Where:
- **w** = weights  
- **X** = input features  
- **b** = bias  

---

### 2️⃣ Sigmoid Function

The sigmoid function converts z into probability:

σ(z) = 1 / (1 + e^-z)

Properties:
- Output range between 0 and 1
- S-shaped curve
- Used to convert linear output into probability

---

### 3️⃣ Cost Function (Binary Cross Entropy)

J = -1/m Σ [ y log(h) + (1-y) log(1-h) ]

Where:
- **y** = actual label
- **h** = predicted probability
- **m** = number of samples

Cross-Entropy is preferred over MSE for classification problems.

---

### 4️⃣ Gradient Descent

Weights and bias are updated using:

w = w - α * dw  
b = b - α * db  

Where:
- **α** = learning rate
- **dw** = derivative w.r.t weights
- **db** = derivative w.r.t bias

Gradient Descent minimizes the cost step by step.

---

## 📊 Dataset Used

The **Breast Cancer Dataset** from Scikit-Learn was used.

Why this dataset?

- It is a binary classification dataset
- It is clean and well structured
- Suitable for Logistic Regression

Data Split:
- 80% Training Data
- 20% Testing Data

Feature scaling was applied using **StandardScaler** for better convergence.

---

## ⚙️ Implementation From Scratch

The following components were implemented manually:

### ✅ Sigmoid Function  
Converts linear output into probability.

### ✅ Parameter Initialization  
Weights initialized to zero.  
Bias initialized to zero.

### ✅ Cost Function  
Binary Cross Entropy implemented manually.

### ✅ Gradient Descent  
Weights updated iteratively using derivatives.

### ✅ Prediction Function  
If probability ≥ 0.5 → Class 1  
Else → Class 0  

---

## 📉 Graphs Included

To better understand model learning, the following graphs were added:

### 📈 Sigmoid Function Graph
- Shows S-shaped curve
- Demonstrates probability conversion

### 📉 Cost vs Iterations Graph
- Shows cost decreasing over time
- Indicates successful learning

### 📊 Confusion Matrix
Displays:
- True Positives
- True Negatives
- False Positives
- False Negatives

Helps evaluate classification performance.

---

## 🤖 Scikit-Learn Implementation

After manual implementation, Logistic Regression was also implemented using:


sklearn.linear_model.LogisticRegression


Purpose:
- Validate manual implementation
- Compare accuracy
- Observe performance difference

---

## 📊 Results

| Model | Accuracy |
|--------|----------|
| From Scratch | ~95%+ |
| Scikit-Learn | ~96%+ |

Both models performed similarly.

---

## 🔍 Comparison

### From Scratch
- Slower
- Deep understanding of mathematics
- Manual implementation

### Scikit-Learn
- Faster
- Optimized
- Ready-to-use implementation

---

## 🏁 Conclusion

In this project:

- Logistic Regression was implemented from scratch
- Mathematical concepts were applied practically
- Learning process was visualized using graphs
- Results were compared with Scikit-Learn

This project improved understanding of:

- Sigmoid Function
- Cross-Entropy Loss
- Gradient Descent
- Model Evaluation Techniques

---

## 🎓 Viva Preparation Questions

Be prepared to answer:

1. Why do we use Sigmoid function?
2. Why is Cross Entropy better than MSE?
3. Why is feature scaling important?
4. Difference between Linear and Logistic Regression?
5. What happens if learning rate is too high?
6. Why is threshold 0.5 used?

---

## 📂 Folder Structure


Fellowship Repository
│
└── Week 5
├── Week5_Logistic_Regression.ipynb
└── README.md


---

## 🚀 How to Run

1. Open Google Colab
2. Upload the notebook
3. Run all cells
4. Observe outputs and graphs

---

## ✅ Final Submission Checklist

- ✔ Single .ipynb notebook
- ✔ From scratch implementation
- ✔ Graphs included
- ✔ Scikit-Learn comparison
- ✔ Clean markdown formatting
- ✔ README added
- ✔ Uploaded to GitHub