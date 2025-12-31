# 🎓 Student Feedback Sentiment Analysis (NLP)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-77ACF1?style=for-the-badge&logo=pandas&logoColor=white)

## 📝 Project Overview
This project analyzes student feedback data to understand faculty performance and student satisfaction. Unlike standard numeric analysis, this project utilizes **Natural Language Processing (NLP)** to interpret text-based feedback and determine the underlying sentiment (Positive, Neutral, Negative).

## ❓ Problem Statement
The college collects survey data, but it consists of mixed numerical ratings and unstructured text. The goal was to:
1.  Quantify subjective feedback using **Sentiment Analysis**.
2.  Identify specific areas where faculty excel or struggle.
3.  Provide data-driven recommendations to improve teaching quality.

## 🛠️ Data Pipeline
1.  **Data Cleaning:** Renamed cryptic column headers to readable metrics.
2.  **Feature Engineering:** Calculated `Overall_Score` and categorized satisfaction levels.
3.  **Data Augmentation:** Generated synthetic text comments based on rating logic to simulate a real-world NLP scenario.
4.  **NLP Analysis:** Used **TextBlob** to calculate Polarity scores for every student comment.
5.  **Visualization:** Built correlation plots (Rating vs. Sentiment) using **Seaborn**.

## 📊 Key Findings
*   **High Satisfaction:** **86.2%** of student feedback was positive.
*   **Faculty Strength:** The strongest metric was **Subject Knowledge**.
*   **Area for Improvement:** The lowest ratings were consistently in **Doubt Solving** and **Assignment Difficulty**.

## 🚀 How to Run
1.  Clone the repository.
2.  Install dependencies: `pip install pandas seaborn textblob`
3.  Run the Jupyter Notebook `Student_Feedback_Analysis.ipynb`.

---
*Created by B Kamachari | Data Analytics Internship Task 3*
