# Multiple Linear Regression

## Project Overview

This project develops a Multiple Linear Regression (MLR) model to examine the relationship between advertising expenditure across different marketing channels and product sales. The analysis includes model development, diagnostic testing, coefficient interpretation, and business recommendations to support marketing budget decisions.

---

## Project Objectives

- Detect and address multicollinearity among predictors.
- Build a statistically robust Multiple Linear Regression model.
- Evaluate predictor significance using p-values and Adjusted R².
- Verify regression assumptions using diagnostic plots.
- Interpret regression coefficients in a business context.
- Provide evidence-based recommendations for marketing budget allocation.

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

1. Data preprocessing and exploration.
2. Encode categorical variables.
3. Assess multicollinearity using Variance Inflation Factor (VIF).
4. Build the Multiple Linear Regression model.
5. Evaluate model performance.
6. Validate regression assumptions using residual diagnostic plots.
7. Interpret model coefficients.
8. Develop business recommendations.

---

## Model Performance

- **Adjusted R²:** 0.903
- The model explains approximately **90.3%** of the variation in Sales, indicating excellent predictive performance and a strong overall fit.

---

## Key Findings

- **Radio advertising** is a statistically significant positive predictor of Sales. Holding other variables constant, a one-unit increase in Radio advertising is associated with an average increase of **2.99 units** in Sales.
- **TV advertising** significantly influences Sales. Compared with High TV advertising, Low and Medium TV advertising levels are associated with significantly lower Sales.
- **Social Media advertising** was not statistically significant (p = 0.824), suggesting that it does not meaningfully contribute to predicting Sales after accounting for Radio and TV advertising.
- Residual diagnostic plots indicate that the assumptions of linearity, homoscedasticity, and normality are reasonably satisfied, supporting the validity of the regression model.

---

## Regression Assumptions

### Linearity
Residuals were randomly scattered around the zero line with no clear systematic pattern, indicating that the linearity assumption was satisfied.

### Homoscedasticity
Residuals exhibited a relatively constant spread across fitted values with no funnel-shaped pattern, suggesting constant error variance.

### Normality
The Q-Q plot showed residuals closely following the reference line, with only slight deviations at the tails. This indicates that the residuals are approximately normally distributed.

---

## Business Recommendation

- Increase investment in **Radio advertising**, as it demonstrated the strongest statistically significant positive effect on Sales.
- Maintain a **High TV advertising** strategy, since reducing TV investment is associated with significantly lower Sales.
- Review and optimise **Social Media campaigns**, as current spending did not significantly improve Sales within this model.
- Future analyses should consider additional variables that may further improve sales prediction and marketing effectiveness.

---

## Conclusion

The Multiple Linear Regression model provides an excellent fit to the data and explains over **90%** of the variation in Sales. Radio advertising and maintaining High TV advertising levels are the most effective strategies for increasing Sales, while Social Media advertising showed no significant impact after controlling for the other marketing channels.
