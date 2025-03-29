# Transaction Tracker – Personal Expense Analysis & Prediction

## Project Overview
This project explores a dataset of personal financial transactions to analyze spending habits and predict expenses using basic machine learning techniques.

Built as a portfolio project to demonstrate data wrangling, visualization, feature engineering, and regression modeling using Python.

---

## Tools & Technologies
- `pandas`, `numpy` – data manipulation
- `matplotlib`, `seaborn` – data visualization
- `scikit-learn` – linear regression model
- `Jupyter Notebook` – interactive development

---

## Project Structure

```
transaction-tracker/
├── data/
│   └── budget_data.csv
├── notebooks/
│   └──01_eda.ipynb       # Exploratory Data Analysis & Visualizations & Linear Regression Model
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Exploratory Data Analysis (EDA)

### Total Spending by Category
- Restaurants and coffee are the top spending categories.

### Weekly Spending Pattern
- Most spending occurs midweek (especially Wednesdays).

### Monthly Spending Trend
- Peak in July; dips in February and November.

---

## Machine Learning Model: Linear Regression

### Goal:
Predict transaction `amount` based on:
- Time-based features: `month`, `day`, `hour`
- Encoded `category`

### Model Performance:
- **Mean Squared Error (MSE)**: `~8270`  
- Shows reasonable accuracy for day-to-day expenses.

### Actual vs Predicted Spending

*![Actual vs Predicted](images/actual_vs_predicted.png)*

---

## Key Takeaways
- Performed feature extraction from datetime
- Applied one-hot encoding for categorical variables
- Improved model accuracy with proper feature engineering
- Created professional-quality visualizations

---

## What I Learned
- Working with real-world transaction data
- Building regression models with `scikit-learn`
- How to go from raw data to deployable project
- Communicating results clearly via visualizations

---

## Author
**[Bassar Baishev]**

---
