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

## Team Information
This project is developed as part of a **Peer Project Assignment**  
Team size: **2–3 members**

---
Day 2 – Dataset Finalization & Requirement Clarification
Overview of Day 2

On Day 2, the team focused on:

Finalizing the dataset

Understanding each feature clearly

Defining system requirements

Deciding how predictions will be generated

Preparing the base structure for implementation

No complex coding was done on Day 2.
This day was mainly about analysis, clarity, and planning before implementation.

Dataset Finalization
Selected Dataset

Dataset Name: House Plants Care Dataset
Source: UCI Machine Learning Repository

After reviewing multiple datasets, this dataset was selected because:

It is simple and beginner-friendly

It represents real-life plant care scenarios

It contains time-based information suitable for reminders

It does not require complex preprocessing

Dataset Description

The dataset contains information related to indoor plants and their watering patterns.

Each record represents a single plant with its care-related details.

Finalized Features (Input Variables)

The following features were finalized for use in the system:

1. Plant Type

Example: Succulent, Fern, Flowering Plant

Different plants require different watering frequencies

This feature helps adjust watering intervals

2. Pot Size

Example: Small, Medium, Large

Larger pots usually retain water longer

Smaller pots dry faster and need more frequent watering

3. Room Temperature

Measured in degrees Celsius

Higher temperature → faster water evaporation

Lower temperature → slower water usage

4. Last Watered Date

The most important time-based feature

Used to calculate days since last watering

Target Output (System Output)

The system will generate:

Next Suggested Watering Date

A clear recommendation such as:

“Water the plant tomorrow”

“No watering needed for 2 more days”

This output will be easy to understand for non-technical users.

Requirement Clarification
Functional Requirements

The system must:

Accept plant care data as input

Calculate days since last watering

Apply simple logic to estimate watering interval

Display the next watering date clearly

Non-Functional Requirements

The system should:

Be easy to understand

Run on basic hardware

Use simple Python libraries

Avoid complex machine learning models

Be suitable for beginners

Prediction Logic (Clarified)

The prediction approach was finalized as:

Calculate the number of days since the plant was last watered

Apply a simple moving average on watering intervals

Adjust the result based on:

Plant type

Pot size

Room temperature

Generate the next watering date

This logic ensures:

No overwatering

No underwatering

Clear and explainable decisions

Tools Confirmation

The following tools were finalized for implementation:

Python (main programming language)

Pandas (data handling)

NumPy (calculations)

Matplotlib (basic visualizations)

Google Colab (execution environment)

Folder & File Structure (Confirmed)

The repository structure was finalized as:

Plant-Watering-Reminder/
│
├── README.md
├── data/
│ └── plants_dataset.csv
├── notebooks/
│ └── analysis.ipynb
└── outputs/
└── results.png

This structure keeps:

Data

Code

Outputs
well-organized and easy to understand

Team Discussion Summary

During Day 2 discussion, the team agreed that:

Simplicity is the main strength of this project

Explainability is more important than complex models

The project should solve a real-life daily problem

The system should be understandable by beginners

Day 2 Status

✔️ Dataset finalized
✔️ Features confirmed
✔️ Requirements clarified
✔️ Prediction logic finalized
✔️ Folder structure confirmed
⏳ Implementation to begin on Day 3
