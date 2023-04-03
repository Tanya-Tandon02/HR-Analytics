# HR-Analytics - Employee Attrition Prediction

The ability to acquire and keep excellent personnel is one of the cornerstones to organizational success. It reduces recruitment expenses and contributes to the overall growth of the organization.
### Benifits from Predictive Modeling in HR:
1. Recognize the strengths and vulnerabilities of the workforce and predict
vacancies and leadership needs.

2. Track and analyze critical skills, and predict which skills will be lost and when
by predicting turnover.

3. Measure turnover, understand its causes and design programs to control it
to reduce vacancy costs – both financial and productivity – to avoid their
devastating effects on business performance.

4. Assess risk on an organization-wide level by integrating workforce and
relevant business and third-party data for comprehensive risk analysis.

5. Build weighted risk factors into strategic human capital management plans
and reduce risk by understanding workforce supply-and-demand patterns.

6. Understand and mitigate risk linked to seasonal absences, resignation trends
or length of employment to prevent being blindsided by loss of critical
workers, skills or leadership.

7. Measure, monitor and predict the effect of risk factors over time and
prevent organizational risk by devising contingency plans based on insight and
foresight. 

## **Objective**

This project aims to discover insights that will help a company make conscious decision about hiring talents and improve employee satisfaction and retention.

## **Dataset**
A dataset consist of 10 columns and 14998 entries. Columns are :

* satisfaction_level: Employee satisfaction level

* last_evaluation: Last evaluation

* number_project: Number of projects

* average_montly_hours: Average monthly hours

* time_spend_company: Time spent at the company

* Work_accident: Whether they have had a work accident

* promotion_last_5years: Whether they have had a promotion in the last 5 years

* department: Department

* salary: Salary

* left: Whether the employee has left

## **Data Understanding**
From Exploratory data analysis the following are the understanding about the dataset:
1. Out of total employees, about 3571 employees left the company.

2. Large number of people leaving the comapny is because of low salary.

3. Large number of people having low satisfaction leaving the company and mostly people with satisfaction less than 0.5.
   So,the comapny need to understand this and deal with these employees with different strategy.

4. People with less experience are not leaving  the comapny but as they growing they start leaving the company and it is highest with 5 years. The reason might be low salary or low satisfaction level.

5. The percent of people leaving the company is evenly distributed across all departments, but the highest is in HR department itself.

## **Machine learning with different classification models**

We tested four different machine learning models to predict employee attrition, including Logistic Regression, Decision Tree, Random Forest, and XGBoost. After feature engineering and hyperparameter tuning we selected the XGBoost model having highest accuracy of 99% for final prediction.

