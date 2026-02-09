# Titanic Dataset – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Titanic dataset.
The main purpose of this analysis is to understand the dataset, explore patterns, and identify key factors that influenced passenger survival during the Titanic disaster.

This EDA is part of **Week 2: Data Handling & Visualization** and is implemented using Python in a Jupyter/Google Colab notebook.

---

## 🎯 Objective
The objectives of this project are:
- To understand the structure of the Titanic dataset
- To analyze missing values
- To explore relationships between survival and different features
- To visualize important patterns using graphs
- To summarize key insights from the data

---

## 📊 Dataset Overview
The Titanic dataset contains information about passengers aboard the Titanic.
The main file used for EDA is:

- **train.csv** – contains passenger data along with survival information

Key features in the dataset include:
- PassengerId
- Survived (0 = Not Survived, 1 = Survived)
- Pclass (Passenger Class)
- Name
- Sex
- Age
- SibSp (Siblings/Spouses aboard)
- Parch (Parents/Children aboard)
- Fare
- Embarked (Port of Embarkation)

---

## 🧪 Exploratory Data Analysis Performed
The following analysis steps were performed in the notebook:

### 1. Data Loading
- The dataset was loaded using Pandas.
- Initial rows were displayed to understand the structure.

### 2. Data Overview
- Dataset shape was checked.
- Column names and data types were examined using `info()`.

### 3. Missing Values Analysis
- Missing values were identified using `isnull().sum()`.
- Age and Cabin columns were found to have missing data.

### 4. Survival Analysis
- Overall survival count was analyzed.
- Visualizations were used to compare survived vs not survived passengers.

### 5. Gender vs Survival
- Survival rates were compared between male and female passengers.
- Female passengers showed a higher survival rate.

### 6. Class vs Survival
- Survival was analyzed based on passenger class.
- First class passengers had a higher survival chance.

### 7. Age Distribution
- Age distribution was visualized using histograms.
- Children showed better survival trends.

---

## 🛠 Tools & Libraries Used
The following Python libraries were used in this project:

- **NumPy** – for numerical operations
- **Pandas** – for data manipulation and analysis
- **Matplotlib** – for basic data visualization
- **Seaborn** – for advanced and statistical visualizations

---

## ▶️ How to Run the Notebook
To run this project on your system or Google Colab:

1. Open Google Colab or Jupyter Notebook
2. Upload the file `EDA_Titanic.ipynb`
3. Upload `train.csv` in the same directory
4. Run all cells from top to bottom

---

## 📁 Project Structure
Week2/
│── EDA_Titanic.ipynb
│── README.md
│── train.csv


---

## 📌 Final Insight
The Exploratory Data Analysis of the Titanic dataset clearly shows that:
- Gender, passenger class, and age were the most important factors affecting survival.
- Female passengers and first-class passengers had significantly higher survival rates.
- Missing data was present and should be handled before applying machine learning models.

---

## ✅ Conclusion
This project successfully demonstrates how Exploratory Data Analysis helps in understanding real-world datasets.
The insights gained from this analysis can be used as a foundation for building predictive machine learning models in later stages.