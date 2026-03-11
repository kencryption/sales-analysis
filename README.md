# 📈 Superstore Profit Prediction

![Python](https://img.shields.io/badge/Python-Data%20Science-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-orange?logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Data-Pandas-black?logo=pandas)
![License](https://img.shields.io/badge/License-MIT-yellow)

A machine learning project that analyzes retail transaction data and predicts **order-level profit** using engineered features and a Gradient Boosting model.

This project follows a complete **data science workflow**, including exploratory analysis, feature engineering, model training, and model evaluation using the **Superstore dataset**.

---

# 🎯 Project Objective

The goal of this project is to:

- Understand **what drives profit in retail transactions**
- Build a **machine learning model to predict order-level profit**
- Extract **business insights from sales data**

---

# 🔎 Exploratory Data Analysis

Key analyses include:

- Profit distribution across orders
- Sales performance by product category
- Regional sales trends
- Discount impact on profit

These analyses help identify variables that influence profitability.

---

# ⚙️ Feature Engineering

Engineered features include:

- **Log transformation of sales (`log_sales`)**
- **Interaction feature between discount and sales**
- **Temporal features (month and day of week)**
- **Unit price and value-per-item features**

These features improve the model's ability to capture patterns related to pricing and behavior of transactions.

---

# 🤖 Profit Prediction Model

### Model Used

**Gradient Boosting Regressor**

### Training Workflow

1. Train-test split
2. Model training
3. Model evaluation
4. Feature importance analysis

### Evaluation Metrics

- **RMSE (Root Mean Squared Error)**
- **R² Score**

The model explains a large portion of the variability in profit and performs well across typical transactions.

---

# 📊 Model Evaluation

## Predicted vs Actual Profit

![Predicted vs Actual Profit](outputs/charts/predicted_profit_vs_actual_profit.png)

This plot compares predicted profit with actual profits. The strong positive relationship indicates that the model successfully captures the overall profitability patterns.

---

## Residual Distribution

![Residual Distribution](outputs/charts/residual_distribution.png)

Residuals are centered around zero indicating that the model does not show strong systematic bias.

---

## Profit Distribution

![Profit Distribution](outputs/charts/profit_distribution.png)

Most transactions generate small positive profits while fewer transactions produce high profits or losses.

---

## Feature Importance

![Feature Importance](outputs/charts/feature_importance.png)

Feature importance analysis shows that sales and discount are among the strongest predictors of profit.

---

# 💡 Key Insights

- Profit margins vary across retail transactions.
- Discounts have a strong impact on profitability.
- Product categories influence profit outcomes.
- Retail profit data is highly variable.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---