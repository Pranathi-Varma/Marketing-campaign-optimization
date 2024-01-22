# Marketing-campaign-optimization
This GitHub repository focuses on training a predictive model to help a company maximize profits in its marketing campaigns. The project evaluates various classification models and selects the best-performing one.

Prerequisites
Before getting started, ensure you have the following dependencies installed:

Python: The project is implemented using Python. Install it on your machine.
Jupyter Notebook: Recommended for running the project interactively.
Libraries: Install required libraries using the following command:

Objectives
Train a predictive model to maximize profits in upcoming marketing campaigns.
Evaluate and choose the best-performing classification model.
Introduction
This presentation highlights strategies to enhance the performance of the marketing team and campaigns. The goal is to utilize marketing budgets more efficiently, achieve a higher return on investment, and gain insights into customer preferences.

Data Set
Utilizes a Marketing Campaign dataset containing customer details and spending habits.
29 features and 2240 rows.
Features include customer response, complaints, education level, marital status, and spending on various products.
Data Processing
Removes duplicate values and addresses null values in the income column.
Performs feature transformations, such as converting birth year to age and customer registration date to customer experience.
Creates dummy columns for marital status and education.
Outliers
Removes clients with over 100 years of age and those with over $200,000 annual spending.
Relation Among Data
Analyzes the relationship between customer response and spending.
Observes that income doesn't always impact the number of purchases, but spending increases with more purchases.
Notes that frequent store visitors tend to spend more, regardless of income.
Correlation
Utilizes a heatmap to identify strong correlations between features.
Addresses multicollinearity using the Variance Inflation Factor (VIF).
Classification Models
Implements Logistic Regression, Linear Discriminant Analysis (LDA), and Quadratic Discriminant Analysis (QDA).
Evaluates models with confusion matrices and ROC curves.
Conclusion
Successfully builds a predictive model for estimating customer acceptance of offers.
LDA shows high accuracy and AUC, making it a preferred classification model.
