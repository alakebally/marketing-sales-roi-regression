# marketing-sales-roi-regression
Simple Linear Regression analysis of marketing data using Python and statsmodels. Includes EDA, model diagnostics, and interpretation of results to generate ROI-based insights for optimizing advertising budget decisions.
# 📊 Marketing ROI Regression Analysis

## 📌 Project Overview

This project applies Simple Linear Regression using Python and `statsmodels` to analyze the relationship between marketing spend and sales. The goal is to identify the most impactful advertising channel and generate data-driven, ROI-based recommendations for optimizing marketing budget allocation.



## 🎯 Objectives

* Analyze the relationship between advertising channels and sales
* Identify the most influential marketing variable
* Build and evaluate a regression model using OLS
* Validate model assumptions
* Translate statistical results into business insights

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* Matplotlib / Seaborn
* Statsmodels

---

## 📂 Project Workflow

### 1. Data Preparation

* Loaded and explored the dataset
* Checked and handled missing values

### 2. Exploratory Data Analysis (EDA)

* Visualized relationships between variables
* Used correlation analysis to identify key predictors

### 3. Model Development

* Selected the most correlated variable (TV advertising)
* Built a Simple Linear Regression model using OLS

### 4. Model Diagnostics

* Residual vs Fitted plot → tested linearity
* Q-Q plot → tested normality of residuals
* Residual distribution → checked homoscedasticity

### 5. Model Interpretation

* Strong model fit (high R²)
* TV advertising is statistically significant (p < 0.001)
* Intercept not statistically significant

---

## 📈 Key Findings

* TV advertising has a strong positive impact on sales
* The model explains a high proportion of variation in sales
* Each unit increase in TV ad spend leads to a significant increase in sales

---

## 💰 Business Recommendation (ROI-Based)

* TV advertising delivers a strong return on investment (~3.55:1)
* Increasing budget allocation toward TV advertising is recommended
* Budget increases should be monitored to avoid diminishing returns

---

## 📎 Project File

* `marketing_and_sales_data_evaluate_lr.ipynb` → full analysis, code, and visualizations

---

## 🚀 Conclusion

This project demonstrates how statistical modeling can be used to transform raw marketing data into actionable business insights. By leveraging regression analysis, companies can make informed decisions to maximize marketing ROI and improve overall performance.

---
