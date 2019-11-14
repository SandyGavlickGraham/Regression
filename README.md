# Regression

I did this regression project as an assignment in Codeup. I need to go back through and improve it with all I've learned since then! This was created in March of 2019.

## Goal: Predict the total charges using the telco_churn database and linear regression.

## Plan
### Summary: Do any features aside from the obvious predict the total charged a customer?
 'gender', 'senior_citizen', 'partner', 'dependents', 'tenure', 'paperless_billing', 'payment_type_id', 'contract_type_id.1', 'contract_type'

### Features that obviously add to the total charged, but do any types of service have a high percentage of high total charges, meaning perhaps they should be marketed?
 'phone_service', 'multiple_lines', 'internet_service_type_id', 'online_security', 'online_backup', 'device_protection', 'tech_support', 'streaming_tv', 'streaming_movies', 'contract_type_id','monthly_charges', 'churn', 'internet_service_type_id.1', 'internet_service_type', 'payment_type_id.1', 'payment_type'

Target = total_charges

### Recommend adding a planning section to the top of your analysis notebook in order to:

- Summarize the project goals. What's the problem you're trying to solve and why is it important?
- Explain your initial hypothesis or hypotheses that you're going to be testing.
- What is your target variable?
- Why, specifically, is that your target variable?
- Specifically explain which features you are going to be using and which features you're going to be ignoring. Be absolutely certain to explain WHY you are using or dropping certain features. For example, "I'll be using contract_type because ...." and "I'll be ignoring monthly_charges because ..."

### Outline the format of the project:
- First, I'm going to prepare/wrangle the data
Second, I'll explore the data looking for meaningful relationships between our independent variables and the target variables. In the exploration, I'll explain and support why the analysis uses A, B, and C features and ignores X, Y, Z features...
- Next, I'll develop a baseline predictive model (first draft model)
- Then, I'll develop a few other models to see if they have more effective and believable predictive power than the baseline model.
- Before we provide a final suggestion, I'll perform additional feature engineering to see if any derived columns or combinations are more useful than the original features.
- Finally, I'll provide a suggestion on which model to use, why, and what stakeholders should take away from this analysis. What's the bottom line recommendation and why?