# Plant Watering Reminder System
### Smart Plant Caretaker (Peer Project – Day 1)

## Project Overview
The **Plant Watering Reminder System** is a simple and practical data science project that helps predict **when a house plant needs water**.  
The goal is to avoid **overwatering** and **underwatering** by using past watering history and basic room conditions.

This project focuses on **simplicity, real-life relevance, and time-based analysis**, making it ideal for short peer projects.

---

## Problem Statement
Many people forget when they last watered their plants or water them too frequently.  
This leads to:
- Weak plant growth
- Root damage
- Plant death

This system provides a **smart reminder** for the next watering day based on historical data.

---

## Project Objective
- Predict the **next watering day** for a house plant  
- Use **past watering dates** and **basic plant/environment features**
- Keep the logic **simple and explainable**
- Apply **time-series concepts** at a beginner level

---

## Project Timeline

### Day 1 – Topic Finalization
On **Day 1**, the team:
- Brainstormed multiple real-life problems
- Selected a **simple, unique, and practical topic**
- Defined the problem statement
- Identified dataset, features, and approach

 **No coding was done on Day 1. Only planning and topic selection.**

---

## Dataset Information
**Dataset Name:** House Plants Care Dataset  
**Source:** UCI Machine Learning Repository  

The dataset contains basic information related to plant care and watering patterns.

---

## Features Used
The following features will be used in the project:
- Plant type  
- Pot size  
- Room temperature  
- Last watered date  

These features help estimate how frequently a plant needs water.

---

## Methodology
The prediction logic is kept intentionally simple:

- Calculate **days since last watering**
- Apply a **simple moving average**
- Adjust watering frequency based on plant type and conditions

This approach avoids complex machine learning models and keeps the system easy to understand.

---

## Expected Output
- Suggested **next watering date**
- Clear recommendation for plant care
- Easy-to-read output for users

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib (for basic visualization)  
- Google Colab  

---

## Why This Project Is Good
- Solves a **daily-life problem**
- Very **easy logic** to understand
- Introduces **time-series concepts**
- Suitable for **short peer projects**
- Beginner-friendly and practical

---

## Future Scope
In future versions, the system can be improved by:
- Adding humidity and sunlight data
- Using machine learning models
- Creating a mobile or web reminder app
- Sending notifications to users

---

## Repository Structure
Plant-Watering-Reminder/
│
├── README.md
├── data/
│ └── plants_dataset.csv
├── notebooks/
│ └── analysis.ipynb
└── outputs/
└── results.png


---

## Team Information
This project is developed as part of a **Peer Project Assignment**  
Team size: **2–3 members**

---

## Status
✔️ Topic finalized  
✔️ Planning completed  
⏳ Implementation starting from Day 2
