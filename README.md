# Churn-Prediction-and-Analysis

## Introduction
This project focuses on analyzing customer churn for a telecom company using a dataset that includes various customer attributes and service usage details. The objective is to understand customer churn patterns and predict the likelihood of churn using data-driven insights.

The project is divided into two main parts:

  **1. Dashboard Creation in Power BI:** An interactive dashboard was developed to visualize and analyze churn-related data, enabling a comprehensive understanding of customer behavior and risk factors.

  **2. Predictive Modeling with Logistic Regression:** A logistic regression model was implemented in Python to predict customer churn. The model's performance was evaluated to assess its accuracy and effectiveness in forecasting churn.

Through this project, key insights into churn patterns were uncovered, and recommendations for reducing churn were formulated based on the analysis.

## Power Bi Dashboard

![Churn Prediction and Analysis](https://github.com/jasonnhat/Churn-Prediction-and-Analysis/blob/main/churn%20dashboard.jpeg)
![Churn Prediction and Analysis](https://github.com/jasonnhat/Churn-Prediction-and-Analysis/blob/main/customer%20risk%20analysis.jpeg)

## Insights form the Dashboard
- **Overall Churn Rate:** The churn rate is 27%, indicating that approximately one-quarter of the customer base is leaving the service.
- **Customer Tenure:** About 55% of churned customers have been with the company for less than 1 year, while only 10% have been customers for more than 5 years. This suggests that shorter-tenured customers are more prone to churn.
- **Contract Type:** Approximately 90% of churned customers have month-to-month contracts. This indicates that customers with more flexible, short-term contracts are more likely to leave.
- **Payment Methods:** The majority of churned customers use non-automatic payment methods, such as electronic checks and mailed checks. This could point to a correlation between payment method and customer retention.
- **Internet Service Type:** The churn rate for customers with fiber optic internet is 18%, which is higher compared to 7% for those with DSL. This suggests that dissatisfaction with fiber optic service may be contributing to higher churn rates.
- **Senior Citizens:** Senior citizens are less likely to churn compared to other age groups, indicating that this demographic is more loyal or satisfied with the service.

## Solution to Reduce Customer Churn
**1. Enhance Customer Retention for New Customers:**
- **Action:** Implement targeted onboarding and engagement programs for customers within their first year.
- **Objective:** Increase the likelihood of retention for customers who are at higher risk of churning due to their short tenure.

**2. Review and Optimize Contract Options:**
- **Action:** Explore offering incentives or benefits for customers to commit to longer-term contracts.
- **Objective:** Reduce churn among customers with month-to-month contracts by providing attractive options for longer-term commitments.

**3. Improve Payment Method Options:**
- **Action:** Promote automatic payment methods and provide incentives for customers to switch from electronic or mailed checks to automatic payments.
- **Objective:** Decrease churn related to payment method dissatisfaction by making automatic payments more convenient and appealing.

**4. Assess and Improve Fiber Optic Service:**
- **Action:** Conduct a thorough review of the fiber optic service to identify and address any issues or areas of dissatisfaction.
- **Objective:** Reduce the higher churn rate associated with fiber optic internet by enhancing service quality and customer support.

**5. Leverage Senior Citizens as a Positive Example**
- **Action:** Develop targeted programs or services that appeal to other customer demographics, drawing on successful strategies used with senior citizens.
- **Objective:** Increase overall customer satisfaction and loyalty by implementing practices that resonate with loyal customer groups.

**6. Enhance Customer Support and Engagement:**
- **Action:** Invest in improving customer support channels and engagement efforts to better address and resolve issues that may lead to churn.
- **Objective:** Address customer concerns more effectively, improving overall satisfaction and reducing the likelihood of churn.

## Logistic Regression
![`ChurnPrediction.ipynb`](https://github.com/jasonnhat/Churn-Prediction-and-Analysis/blob/main/ChurnPrediction.ipynb)
