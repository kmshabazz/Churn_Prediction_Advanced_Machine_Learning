# Churn_Prediction_Advanced_Machine_Learning
Analyze the data and come up with a predictive model to determine if a customer will leave the credit card services or not and the reason behind it
# Skills & Tools Covered
EDA, RANDOM FOREST, Bagging, Boosting, SMOTE, Cross Validation, Data Preprocessing, Hyperparameter Tuning
# Background
Thera Bank, a financial institution, recently experienced a significant decline in the number of credit card users, which poses a financial risk. Credit cards are an important revenue source for the bank, as they generate income from various fees such as annual fees, balance transfer fees, cash advance fees, late payment fees, and foreign transaction fees.
# Business Problem
The reduction in credit card users could lead to a loss in revenue. The bank seeks to analyze customer data and pinpoint factors contributing to churn in order to retain customers and improve services. 
# Solution
Develop a classification model that accurately predicts customer churn and provides actionable insights. The model will help Thera Bank identify customers at risk of leaving their credit card services and inform retention strategies that can mitigate churn.
# Data Overview
Dataset Shape: 10127 rows containing 21 columns of data
<br> Datatypes in dataset: floats, integers, objects
<br> Statistical Summary:
<br> ● The average customer age is 46.3 years, with a range between 26 and 73 years.
<br> ● The majority of customers have 2 to 3 dependents (25th percentile: 1, 75th percentile: 3).
<br> ● The average Credit Limit is around $8,631, with a wide range, from $1,438 to $34,516.
<br> ● Total Transactions Count (Total_Trans_Ct) has a median of 67, with a high variability (minimum of
10 and maximum of 139).
<br> ● The Average Utilization Ratio has a mean of 0.275, with 75% of customers having a utilization rate
below 0.503, indicating relatively conservative credit usage.
# Final Model Selection
For the final model, I would choose XGBoost due to its superior performance, scalability, and ability to handle imbalanced datasets. It consistently provided high recall scores across both training and validation sets, indicating its robustness in predicting the positive class (attrition cases) accurately.
<br> Model Performance:
<br> ● Recall on validation data: ~0.97
<br> ● The high recall score ensures that the model correctly identifies a majority of customers likely to churn, which is critical for taking
preemptive retention actions. Business Relevance:
<br> ● Proactive Customer Retention: By accurately predicting attrition, the business can focus its retention efforts on high-risk customers, offering them targeted incentives or personalized outreach to prevent churn.
<br> ● Cost Efficiency: Identifying potential attrition early enables the business to allocate resources effectively, focusing on customers most likely to leave rather than adopting broad, inefficient retention strategies.
# Project Final File:
[Kalifa Shabazz_Predicting Customer Churn_September 2024.pdf](https://github.com/user-attachments/files/18386715/Kalifa.Shabazz_Predicting.Customer.Churn_September.2024.pdf)
