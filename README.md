# Credit Default Risk Modeling

### Credit Risk Analytics | Machine Learning | Python

## Project Overview

This project focuses on analyzing credit card customer behavior and developing predictive models to estimate the probability of credit default.

Using historical financial and payment information, the analysis aims to identify key credit risk drivers, compare machine learning algorithms, and evaluate their ability to distinguish between customers with different levels of default risk.

The project combines statistical analysis, predictive modeling, and business-oriented risk assessment.

## Dataset

**Source:** [UCI Machine Learning Repository – Default of Credit Card Clients](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients)

The dataset contains information on 30,000 credit card customers, including:

- Credit limits and demographic characteristics.
- Historical repayment status.
- Monthly billing amounts.
- Previous payment amounts.
- Default payment indicator for the following month.

**Target variable:** Default payment next month (1 = Default, 0 = No Default).

## Methodology

**1. Exploratory Data Analysis (EDA)**

Analyzed customer characteristics, payment behavior, credit utilization, and historical delinquency patterns to identify potential indicators of credit default.

**2. Feature Engineering and Selection**

Developed behavioral risk indicators and evaluated predictive variables using Information Value (IV), correlation analysis, and business relevance.

**3. Predictive Modeling**

Developed and compared three classification algorithms:

- Logistic Regression
- Random Forest
- Gradient Boosting

**4. Model Evaluation and Calibration**

Evaluated predictive performance and probability estimates using:

- ROC-AUC and Gini Coefficient
- Kolmogorov–Smirnov (KS) Statistic
- Precision-Recall analysis
- Brier Score and Log Loss
- Probability calibration

**5. Credit Risk Segmentation**

Analyzed predicted default probabilities and observed default rates across credit limit segments to assess model behavior and potential business applications.

## Tools & Technologies

- **Python:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Statistical Analysis:** Correlation Analysis, Information Value (IV), Model Evaluation
- **Machine Learning:** Logistic Regression, Random Forest, Gradient Boosting
- **Credit Risk Analytics:** Probability of Default (PD), Portfolio Segmentation, Model Calibration

## Business Applications

The project illustrates how predictive analytics can support:

- Identification of customers with higher default risk.
- Credit portfolio monitoring and segmentation.
- Risk-based credit decision support.
- Evaluation of predictive model performance and reliability.

## References

Yeh, I. C., & Lien, C. H. (2009). *The comparisons of data mining techniques for the predictive accuracy of probability of default of credit card clients.* Expert Systems with Applications, 36(2), 2473–2480.

[UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients)
