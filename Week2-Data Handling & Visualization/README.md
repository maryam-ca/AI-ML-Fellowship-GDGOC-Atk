# 📊 Week 2: Data Handling & Visualization

## Exploratory Data Analysis (EDA) on Titanic Dataset

---

## Project Overview

This project is part of **Week 2** of the Data Science learning plan.  
The main purpose of this week is to build a strong foundation in **data handling, data cleaning, and data visualization** using Python.

In this task, **Exploratory Data Analysis (EDA)** is performed on the famous **Titanic dataset** to understand passenger data and analyze the factors that influenced survival.

This project focuses on:
- Understanding real-world datasets  
- Cleaning and preparing data  
- Discovering patterns through visualization  

---

## Learning Goals of Week 2

The key learning goals of this week are:

- Understanding datasets and data types  
- Using NumPy for numerical operations  
- Using Pandas for data processing  
- Cleaning and preparing real-world data  
- Visualizing data using Matplotlib and Seaborn  
- Extracting insights from data through EDA  

---

## Dataset Overview

The **Titanic dataset** contains information about passengers who traveled on the Titanic ship.

### Dataset Features

- PassengerId  
- Survived (Target Variable)  
- Pclass (Passenger Class)  
- Name  
- Sex  
- Age  
- SibSp (Siblings / Spouses aboard)  
- Parch (Parents / Children aboard)  
- Fare  
- Embarked  

### Target Variable

- **Survived**
  - 0 → Passenger did not survive  
  - 1 → Passenger survived  

---

## Problem Statement

The goal of this analysis is to understand:

- Which factors affected passenger survival  
- How gender, age, class, and fare influenced survival chances  
- What patterns can be observed before applying machine learning models  

Exploratory Data Analysis helps answer these questions by visually and statistically exploring the data.

---

## Tools and Libraries Used

The following tools and libraries were used during this project:

- **Python**  
- **NumPy** – For numerical calculations  
- **Pandas** – For data loading, cleaning, and manipulation  
- **Matplotlib** – For basic data visualization  
- **Seaborn** – For advanced and statistical visualizations  
- **Google Colab** – For running the Jupyter Notebook  

---

## Notebook Structure

The Jupyter Notebook is carefully organized into the following sections:

---

### Data Loading and Inspection

- Loading the Titanic dataset  
- Viewing sample records using head()  
- Checking dataset shape (rows and columns)  
- Understanding column data types using info()  

---

### Understanding Data Types

- Identifying numerical features  
- Identifying categorical features  
- Understanding the target variable (Survived)  

---

### Data Cleaning and Preparation (Chapter 7)

- Checking missing values in the dataset  
- Handling missing values in the Age column  
- Dropping unnecessary columns such as Cabin  
- Encoding categorical variables like Sex  
- Preparing a clean dataset for analysis  

---

### Exploratory Data Analysis (EDA)

- Survival analysis based on gender  
- Survival analysis based on passenger class  
- Distribution analysis of Age and Fare  
- Feature-wise comparison to identify trends  

---

### Data Visualization (Chapter 9)

- Bar charts to compare survival rates  
- Histograms for age distribution  
- Pie charts for survival proportion  
- Box plots for fare and age comparison  
- Heatmap to analyze feature correlation  

---

### Strategies and Insights (Throughout Notebook)

During the notebook, **2–3 line insights** are added after major steps to explain:

- Key observations  
- Patterns and trends discovered  
- Relationships between features and survival  

---

## Key Insights from the Analysis

Some important insights discovered during EDA are:

- Female passengers had a significantly higher survival rate than males  
- Passengers traveling in first class had better survival chances  
- Age and fare showed noticeable influence on survival  
- Data visualization made patterns easier to understand than raw tables  

---

## How to Run the Notebook

Follow these steps to run the project:

1. Open **Google Colab**  
2. Upload the `EDA_Titanic.ipynb` notebook  
3. Upload the Titanic dataset CSV file  
4. Run all cells from top to bottom  
5. Read markdown explanations and insights  

---

## Repository Structure

Week2/
│
├── EDA_Titanic.ipynb
├── README.md
└── titanic.csv


---

## Submission Guidelines

- One complete Jupyter Notebook (.ipynb)  
- Notebook created using Google Colab  
- Uploaded to GitHub as part of Week 2 work  
- Proper markdown headings and clean code  
- Insights and observations included  

---

## Conclusion

This Week 2 project provided hands-on experience in **data handling, cleaning, and visualization**.  
Exploratory Data Analysis on the Titanic dataset helped in understanding how real-world data behaves and how meaningful insights can be extracted before applying machine learning models.

---
