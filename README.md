# Customer Churn Prediction for SyriaTel
#Author : Martin Kabare

## Table of Contents
1. [Overview](#overview)
2. [Business Understanding](#business-understanding)
3. [Data Understanding](#data-understanding)
4. [Data Preparation](#data-preparation)
5. [Modeling](#modeling)
6. [Evaluation](#evaluation)
7. [Conclusion](#conclusion)
8. [Recommendation](#recommendation)
9. [Next Steps](#next-steps)

### Overview:
The goal of the following project is to predict unhappy customers-that is, those who are likely to churn-using some prespecified data for a predictive model on SyriaTel, a telecommunications company. In being able to predict which customers are churning, the company can take proactive measures toward customer retention and reduce losses in revenue that would consequently result in higher customer satisfaction.

### Business Understanding:
The main business problem then would be churning customers and, in turn, affecting the financial results of SyriaTel. It will try a classifier to predict churn and enable the firm to take precautions.

### Data Understanding:
The dataset has 3333 rows and 21 columns of customer demographic, usage pattern, and service-related information. The major variables are account length, total charges, customer service calls, and whether or not a customer churned.

### Data Preparation:
Cleaning would involve handling missing values, encoding categorical variables, and scaling numerical features. Important key correlations and distributions were found in EDA, hence setting a very good base for modeling.

### Modeling:
### Modeling
Three models have been trained and tested:

Logistic Regression: Reasonable accuracy with insight given on feature importance
Decision Tree: Slightly better, but with a risk of overfitting
Random Forest: Best performance; higher in terms of both accuracy and recall
Evaluation
The best model selected amongst all these was the Random Forest, which had a recall of 0.79 and AUC-ROC of 0.90. This correctly classified 79% of churning cases and was thus well preferred.

### Conclusion:
The Random Forest model should be deployed since it's the best predictor of churn. This will immensely cut down SyriaTel's customer loss.

### Recommendation:
Target states that have higher churn rates with specific promotions.
Re-evaluate pricing models, especially in key areas such as day and international charges.
Provide superior customer service in states where a greater tendency to churn has been noticed.
Final Steps
Model Refinement: More work may be performed with regards to hyperparameters tuning and also other models such as XGBoost. Feature Engineering: Construction of new features may be performed for better prediction. Deployment: Deploying the Random Forest model

### Next Steps:
Model Refinement: Further tune hyperparameters and explore additional models like XGBoost.
Feature Engineering: Incorporate new features that could improve prediction accuracy.
Deployment: Implement the Random Forest model in SyriaTel's production environment and monitor its performance.




