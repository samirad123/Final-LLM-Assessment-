# Final-LLM-Assessment-

# Employee Sentiment Analysis

This repository contains an end-to-end **Employee Sentiment Analysis** project built using Python.  
The goal is to analyze unlabeled employee email messages to understand sentiment, engagement trends, identify potential flight risks, and model sentiment behavior using machine learning.

---

## 📌 Project Objectives

The project addresses the following objectives:

- Automatically label employee messages as **Positive**, **Neutral**, or **Negative**
- Perform **Exploratory Data Analysis (EDA)** with visual insights
- Calculate **monthly sentiment scores** for each employee
- Rank employees based on sentiment performance
- Identify **flight risk employees** using a rolling 30-day window
- Build a **linear regression model** to analyze sentiment trends

---

## 📂 Repository Structure

├── Employee_Sentiment_Analysis.ipynb # Main Jupyter Notebook
├── test.csv # Input dataset (unlabeled)
├── README.md # Project documentation
└── visualizations/ # Generated plots (optional)


---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone <repository-url>
cd employee-sentiment-analysis


python -m venv venv
source venv/bin/activate        # macOS/Linux
venv\Scripts\activate           # Windows


pip install pandas numpy matplotlib seaborn scikit-learn textblob
python -m textblob.download_corpora
Employee_Sentiment_Analysis.ipynb
