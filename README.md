# 🏦 Bank Customer Churn Analysis with GenAI Chatbot

## 📌 Project Overview

This project analyzes customer churn data from a retail bank using Python and Jupyter Notebook. The goal is to explore the dataset to understand customer behavior and churn patterns, and to integrate a Generative AI-powered chatbot within the notebook that can answer natural language questions based on the analysis.

---

## 🎯 Objectives

- Perform exploratory data analysis (EDA) on bank customer churn data
- Visualize patterns and trends related to churn (e.g. age, geography, balance, creditscore)
- Enable a conversational interface using GenAI (OpenAI GPT or similar) to answer business-oriented questions directly in the notebook

---

## 🗃️ Dataset Description

**Filename:** `Bank_Churn.csv`  
**Rows:** 10,000+ bank customers  
**Target Variable:** `Exited` (1 = Churned, 0 = Stayed)

| Column Name        | Description                          |
|--------------------|--------------------------------------|
| `CustomerId`        | Unique identifier for the customer   |
| `Surname`           | Customer's surname                  |
| `CreditScore`       | Credit score (numerical)            |
| `Geography`         | Country of residence                |
| `Gender`            | Gender (Male/Female)                |
| `Age`               | Customer's age                      |
| `Tenure`            | Years with the bank                 |
| `Balance`           | Account balance                     |
| `NumOfProducts`     | Number of bank products held        |
| `HasCrCard`         | Has a credit card (1 = Yes)         |
| `IsActiveMember`    | Whether the customer is active      |
| `EstimatedSalary`   | Annual estimated salary             |
| `Exited`            | Churn indicator (1 = left bank)     |

---

## 🧠 Key Features

### 1. Exploratory Data Analysis
- Churn distribution and churn rate
- Age, geography, and balance analysis by churn status
- Visualizations: bar plots, boxplots, histograms

### 2. Generative AI Chatbot
- Built directly into the Jupyter Notebook
- Powered by OpenAI's GPT (or similar LLM)
- Accepts natural language questions such as:
  - "Which age group has the highest churn rate?"
  - "Do active members churn less?"
  - "Summarize three main reasons for churn based on the data"

---

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- Gemini API (or other LLM)

---

## Sample Output

    📉 Overall Churn Rate: 20.4%

    🌍 Geography Breakdown:

        Germany shows the highest churn rate at 32.1%

        France and Spain have lower churn rates at 16.2% and 18.7% respectively

  ##  💬 Sample Chatbot Q&A:

    User: "What types of customers are most likely to churn?"

    Chatbot:

        "Customers from Germany, aged over 45, with high balances but low product engagement, and who are inactive, show the highest churn risk."

    User: "Give me one strategy to reduce churn."

    Chatbot:

        "Target inactive older customers with personalized engagement campaigns and incentives to adopt more products."

## 🚀 How to Run the Notebook

1. **Clone the repository**
```bash
git clone https://github.com/tenzinyeshay/Python-bank-churn-genai.git
cd bank-churn-genai

