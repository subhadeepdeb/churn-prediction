# Customer Churn Prediction (End-to-End ML System)

## Problem
Customer churn is a major driver of revenue loss for subscription-based businesses.  
The goal of this project is to **predict customer churn** and identify high-risk customers early so retention teams can take proactive action.

## Data
- Dataset: Telco Customer Churn
- Records: ~7,000 customers
- Target: Churn (Yes / No)

## Approach
1. Exploratory data analysis to understand churn drivers
2. Feature preprocessing using scikit-learn pipelines
3. Baseline model: Logistic Regression
4. Nonlinear model: Random Forest
5. Evaluation using ROC-AUC and business-driven thresholding

## Models & Performance
| Model | ROC-AUC |
|------|--------|
| Logistic Regression | 0.847 |
| Random Forest | 0.840 |

Logistic Regression performed slightly better while offering superior interpretability.

## Key Insights
- Month-to-month contracts show significantly higher churn
- Short tenure and higher monthly charges increase churn risk
- Service add-ons (OnlineSecurity, TechSupport) reduce churn likelihood

## Business Impact
By targeting the top 30% highest-risk customers identified by the model, retention teams can prioritize interventions and potentially reduce revenue loss due to churn.

## Tools & Skills
Python, Pandas, scikit-learn, Machine Learning, Feature Engineering, A/B Testing concepts, Data Pipelines


