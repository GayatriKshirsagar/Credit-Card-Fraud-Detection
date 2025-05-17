# 💳 Credit Card Fraud Detection

## 📝 Overview
This project analyzes ~1.85 million credit card transactions to detect fraudulent behavior using data preprocessing and exploratory data analysis (EDA). It includes detailed visualizations to uncover patterns by amount, category, gender, age, and time.

## 📁 Dataset
- Source: `fraudTrain.csv` and `fraudTest.csv` (combined)
- Records: 1,852,394 transactions
- Target: `is_fraud` (1 = Fraud, 0 = Not Fraud)

## 🔍 Key Insights
- 💰 Most fraud occurs in low-value transactions under $538.
- 🧍‍♂️ Male users show a slightly higher fraud tendency.
- 🛒 Categories like `kids_pets` and `grocery_pos` show notable fraud.
- 🕛 Fraud peaks around hour 23 and is higher on weekends.

## 📊 Visualizations
- Histogram: Transaction Amount vs Fraud
- Bar Plot: Fraud % by Transaction Category
- KDE Plot: Age Distribution in Fraud Cases
- Time Analysis: Hour, Day, and Month vs Fraud Rates

## 🛠️ Tech Stack
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `datetime`

## 🚀 How to Run
```bash
git clone https://github.com/GayatriKshirsagar/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook Credit\ Card\ Fraud\ EDA.ipynb
