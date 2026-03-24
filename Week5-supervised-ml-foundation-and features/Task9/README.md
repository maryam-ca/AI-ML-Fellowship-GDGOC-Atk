Logistic Regression Implementation (From Scratch + Scikit-Learn)
📌 Project Overview

This project presents a complete implementation of Logistic Regression for binary classification, developed both from scratch using NumPy and using Scikit-Learn for validation.

The main objective of this project is to understand the mathematical foundation of Logistic Regression by manually implementing all core components before comparing the results with a library-based implementation.

This project was completed as part of the Week 5 AI/ML Fellowship Assignment.

🎯 Project Objectives

Understand the working principle of Logistic Regression

Implement the Sigmoid activation function manually

Implement Binary Cross Entropy loss

Apply Gradient Descent optimization

Train and evaluate the model

Compare results with Scikit-Learn

Visualize learning behavior using graphs

📚 Theoretical Background
What is Logistic Regression?

Logistic Regression is a supervised machine learning algorithm used for binary classification problems.

Unlike Linear Regression, which predicts continuous values, Logistic Regression predicts probability values between 0 and 1.

Decision Rule:

If probability ≥ 0.5 → Class 1

If probability < 0.5 → Class 0

Common applications include:

Spam Detection

Disease Prediction

Fraud Detection

Customer Churn Prediction

🧠 Mathematical Formulation
1️⃣ Hypothesis Function

The linear model is defined as:

z = wX + b

Where:

w = weights

X = input features

b = bias

2️⃣ Sigmoid Function

The sigmoid function transforms the linear output into probability:

σ(z) = 1 / (1 + e^-z)

Properties:

Output range: (0, 1)

Non-linear S-shaped curve

Enables probabilistic interpretation

3️⃣ Cost Function (Binary Cross Entropy)
J = -1/m Σ [ y log(h) + (1 - y) log(1 - h) ]

Where:

y = true label

h = predicted probability

m = number of samples

Binary Cross Entropy is preferred over Mean Squared Error because it provides stronger gradients and better convergence for classification tasks.

4️⃣ Gradient Descent Optimization

Parameter updates:

w = w - α * dw
b = b - α * db

Where:

α = learning rate

dw = derivative with respect to weights

db = derivative with respect to bias

Gradient Descent minimizes the cost function iteratively until convergence.

📊 Dataset Description

The Breast Cancer Dataset from Scikit-Learn was used.

Reasons for selection:

Binary classification problem

Clean and structured dataset

Suitable benchmark dataset

Data preprocessing steps:

80% training data

20% testing data

Feature scaling using StandardScaler

⚙️ Implementation Details (From Scratch)

The following components were implemented manually:

Sigmoid Function

Parameter Initialization

Binary Cross Entropy Loss

Gradient Computation

Gradient Descent Optimization

Prediction Function

Classification rule:

If probability ≥ 0.5 → Class 1
Else → Class 0
📸 Screenshots

Replace the placeholders below with your actual image paths after uploading screenshots to GitHub.

Notebook Output Preview
![Notebook Output](images/notebook_output.png)
Cost vs Iterations Graph
![Cost Graph](images/cost_vs_iterations.png)
Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)
📊 Model Performance Visualization

The following visualizations were generated:

📈 Sigmoid Curve

Demonstrates how linear outputs are converted into probabilities.

📉 Cost vs Iterations

Shows gradual decrease in loss, indicating successful learning and convergence.

📊 Confusion Matrix

Displays:

True Positives

True Negatives

False Positives

False Negatives

📌 Accuracy Comparison
Model	Accuracy
From Scratch	~95%+
Scikit-Learn	~96%+

The similar accuracy confirms correctness of the manual implementation.

🤖 Scikit-Learn Implementation

The model was also implemented using:

sklearn.linear_model.LogisticRegression

Purpose:

Validate manual implementation

Compare performance

Observe computational efficiency

Scikit-Learn provides an optimized and production-ready implementation.

🔍 Comparative Analysis
From Scratch Implementation

Slower training

Strong conceptual understanding

Manual control over optimization

Scikit-Learn Implementation

Faster execution

Highly optimized

Suitable for real-world applications

🏁 Conclusion

This project demonstrates a complete academic and practical implementation of Logistic Regression.

Key learnings include:

Mathematical modeling

Loss optimization using Gradient Descent

Importance of feature scaling

Model evaluation techniques

Performance comparison with industry-standard tools

The project significantly strengthened understanding of classification algorithms.

🎓 Viva Preparation Questions

Be prepared to answer:

Why is the Sigmoid function used?

Why is Cross Entropy better than MSE for classification?

Why is feature scaling important?

What happens if the learning rate is too high?

Why is threshold 0.5 commonly used?

Difference between Linear and Logistic Regression?

📂 Project Structure
Fellowship Repository
│
└── Week5
    ├── Week5_Logistic_Regression.ipynb
    ├── README.md
    └── images/
🚀 How to Run

Open Google Colab

Upload the notebook

Run all cells sequentially

Observe training progress and visualizations

✅ Final Submission Checklist

✔ From scratch implementation
✔ Mathematical explanation
✔ Visualizations included
✔ Scikit-Learn comparison
✔ Clean GitHub formatting
✔ Academic documentation