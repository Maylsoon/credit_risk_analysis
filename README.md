# credit_risk_analysis
Exploratory data analysis and preprocessing for a credit risk prediction project.

## Project Overview

This project presents an exploratory data analysis focused on understanding factors related to credit default risk.
The analysis includes data cleaning, preprocessing, exploratory visualizations, and treatment of class imbalance using SMOTE.
The goal is to extract meaningful insights and prepare the dataset for future modeling steps.

## Business Problem

Financial institutions need to understand which customer characteristics are associated with higher credit default risk.
Identifying these patterns helps support better credit decisions and risk mitigation strategies.
This project explores how demographic and financial variables relate to credit default behavior.

## Dataset

The dataset contains customer demographic, financial, and credit-related information, including income, age, education level, marital status, property ownership, and credit score.
The target variable represents whether a customer is in default or not.

## Analysis and Methodology

The analysis follows a structured workflow:
- Data cleaning and validation of numerical and categorical variables
- Treatment of missing values using statistical criteria
- Exploratory univariate and bivariate analysis with visual support
- Careful interpretation of correlations without assuming causality
- Encoding of categorical variables based on their nature (binary, ordinal)
- Train-test split with stratification
- Handling class imbalance using SMOTE applied only to the training set

## Key Insights

- Income shows a strong relationship with default rates, indicating higher risk among lower income groups.
- Education level, marital status, and property ownership present meaningful correlations with credit behavior.
- Some variables are correlated with each other, reinforcing the importance of careful interpretation and avoidance of causal assumptions.
- Extreme values were analyzed and deliberately kept, as they represent legitimate financial profiles.

## Conclusion

This analysis demonstrates the importance of combining technical rigor with analytical reasoning.
Rather than focusing only on metrics and visualizations, the project emphasizes interpretation, business context, and responsible analytical decisions.
The dataset is now well-prepared for future predictive modeling.

## Next Steps

- Test different encoding strategies such as One-Hot Encoding for sensitive models
- Train and evaluate classification models
- Compare model performance before and after class balancing
- Extend the analysis with model explainability techniques

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook
