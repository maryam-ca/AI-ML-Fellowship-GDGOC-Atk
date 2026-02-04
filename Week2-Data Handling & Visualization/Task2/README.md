# Task 2 – Dataset Basics & Data Handling (Week 2 – Day 2)

---

## 📌 Overview

This task is part of **Week 2** of the **AI/ML Fellowship Program**.  
The main goal of this task was to understand how raw data is prepared and handled before applying machine learning models.

In this task, **NumPy** and **Pandas** libraries were used to explore and analyze data in **Google Colab**.  
The focus was on learning how datasets are structured, how numerical data is processed, and how meaningful insights can be extracted from tabular data.

This task helps build a strong foundation for future topics such as **data cleaning, data visualization, and machine learning algorithms**.

---

## 🎯 Task Objectives

The main objectives of this task were:

- To understand how datasets are structured (rows and columns)
- To learn how to use **Google Colab** for data analysis
- To handle numerical data using **NumPy**
- To analyze tabular data using **Pandas DataFrames**
- To apply basic data handling and filtering techniques
- To identify patterns and insights from real-world data

---

## 🛠️ Tools & Technologies Used

- **Python**
- **Google Colab**
- **NumPy**
- **Pandas**
- **Titanic Dataset (CSV format)**

---

## 📊 Dataset Description

The **Titanic dataset** was used for this task.  
It contains information about passengers, including:

- Passenger class (`Pclass`)
- Gender (`Sex`)
- Age (`Age`)
- Survival status (`Survived`)

This dataset is commonly used for learning data analysis and machine learning concepts.

---

## 🔢 NumPy Usage

NumPy was used to handle numerical data efficiently.

### Tasks Performed:
- Creation of numerical arrays
- Calculation of **mean (average)**
- Calculation of **median (middle value)**

These operations helped in understanding how numerical summaries of data are calculated.

---

## 🧾 Pandas Usage

Pandas was used to work with structured, tabular data through **DataFrames**.

### Tasks Performed:
- Loading the dataset using `read_csv()`
- Viewing dataset structure using `head()` and `columns`
- Selecting single and multiple columns
- Filtering data using conditions
- Using `value_counts()` to count categorical values
- Grouping data using `groupby()` for analysis

---

## 🔍 Data Analysis Performed

The following analyses were conducted:

### ✔ Column Selection
- Selected relevant columns such as `Sex`, `Age`, `Survived`, and `Pclass`

### ✔ Data Filtering
- Filtered passengers based on gender
- Filtered passengers based on survival status

### ✔ Value Counts
- Counted the number of male and female passengers
- Counted the number of survived and non-survived passengers

---

## 📈 Survival Rate Analysis

### Survival Rate by Gender
- Calculated survival rate for male and female passengers
- Found that **female passengers had a significantly higher survival rate** compared to males

### Survival Rate by Passenger Class
- Analyzed survival rates based on passenger class
- First class passengers showed a higher survival rate compared to second and third class passengers

---

## 📌 Key Insight

**Female passengers had a higher survival rate as compared to male passengers.**  
Additionally, passengers traveling in **first class** had a better chance of survival.

These insights demonstrate how simple data analysis can reveal important real-world patterns.

---

## 🧠 Learning Outcome

Through this task, I learned:

- How raw data is prepared for machine learning
- How numerical and categorical data is handled using NumPy and Pandas
- How to explore and filter datasets efficiently
- How data preprocessing and analysis form the backbone of effective AI and machine learning models

---

## ✅ Conclusion

This task strengthened my understanding of **dataset basics and data handling techniques**.  
It provided hands-on experience with real data and highlighted the importance of data preprocessing before applying machine learning algorithms.

---

📅 **Week:** 2  
📘 **Day:** 2  
📂 **Task:** Dataset Basics & Data Handling
