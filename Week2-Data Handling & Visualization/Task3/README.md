# Task 3 – Data Cleaning & Preparation (Week 2 – Day 3)

## Overview

This task is part of **Week 2** of the **AI/ML Fellowship Program**.  
The main focus of this task is to understand how raw datasets are cleaned and prepared before applying any machine learning model.

In this task, the Titanic dataset was used to practice real-world data cleaning techniques using **Python**, **Pandas**, and **Google Colab**.

Data cleaning is a very important step because machine learning models cannot work properly with missing or unprocessed data.

---

## Task Objectives

The main objectives of this task are:

- To understand the concept of missing values in a dataset  
- To learn how to identify missing data using Pandas  
- To handle missing values using appropriate techniques  
- To convert categorical data into numerical format  
- To remove unnecessary columns from the dataset  
- To prepare a clean and model-ready dataset  

---

## Dataset Used

The **Titanic dataset (train.csv)** from Kaggle was used in this task.

This dataset contains information about passengers such as:

- Passenger class  
- Gender  
- Age  
- Number of siblings and parents  
- Fare  
- Cabin information  
- Embarkation port  

---

## Tools & Libraries

The following tools and libraries were used:

- **Google Colab** – for running Python code online  
- **Python** – programming language  
- **Pandas** – for data manipulation and analysis  
- **NumPy** – for numerical operations  

---

## Step 1: Loading the Dataset

The dataset (`train.csv`) was uploaded to Google Colab and loaded using Pandas.

The `head()` function was used to view the first few rows and understand the structure of the data.

---

## Step 2: Checking Missing Values

Missing values were identified using the following method:

- `isnull().sum()`

This helped in finding which columns contain missing data and how many values are missing in each column.

---

## Step 3: Handling Missing Values

Different strategies were used based on the nature of the data:

### Age Column
- The **median value** of the Age column was used to fill missing values.
- Median was chosen because it is less affected by outliers.

### Cabin Column
- The Cabin column contained a large number of missing values.
- Due to insufficient data, this column was **dropped** from the dataset.

### Embarked Column
- The Embarked column had a small number of missing values.
- These were filled using the **mode (most frequent value)**.

---

## Step 4: Converting Categorical Data

Machine learning models work with numerical data, so categorical values were converted:

- The **Sex** column was converted into numeric form:
  - Male → 0  
  - Female → 1  

This makes the data suitable for further analysis and modeling.

---

## Step 5: Removing Unnecessary Columns

Some columns were not useful for analysis or model training, so they were removed:

- PassengerId  
- Name  
- Ticket  

Removing unnecessary columns helps in reducing noise and improving model performance.

---

## Final Data Status

After completing all cleaning steps:

- All missing values were handled  
- All required columns were numeric  
- Unnecessary columns were removed  
- The dataset became **clean, structured, and model-ready**

---

## Learning Outcome

Through this task, the following concepts were learned:

- Importance of data cleaning in machine learning  
- Practical handling of missing values  
- Difference between mean, median, and mode  
- Handling categorical and numerical data  
- Preparing a dataset for the next machine learning steps  

---

## Insight

Handling missing values is a critical step in both data analysis and machine learning.  
If data is not cleaned properly, models can produce incorrect or biased results.  
Proper data preparation leads to more accurate and reliable outcomes.