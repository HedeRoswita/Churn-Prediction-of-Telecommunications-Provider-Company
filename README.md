# Churn-Prediction of Telecommunications Provider Company

Churn prediction is the process of identifying customers who are at risk of churning, or canceling their subscription to a service. Churn prediction is important for businesses because it can help them to reduce customer churn and increase customer lifetime value.

There are a variety of machine learning algorithms that can be used for churn prediction. Some of the most popular algorithms include logistic regression, support vector machines, and random forests. These algorithms can be trained on historical data to identify patterns that are associated with customer churn.

Once a churn prediction model has been trained, it can be used to predict the probability that a customer will churn in the future. This information can then be used to target customers with retention campaigns or to offer them incentives to stay.

Churn prediction is a valuable tool for businesses of all sizes. It can help businesses to reduce customer churn, increase customer lifetime value, and boost profits.

# 1. Objective:

The objective of this project is to identify customer behaviors that indicate a risk of churn and to build predictive models that can be used to predict whether a customer is likely to switch providers. The results of this project can be used by the company to improve their product and to retain their customers.

# 2. Methods:

The following machine learning algorithms will be used to build the predictive models:
- Logistic Regression
- Random Forest
- XGBoost
- Support Vector Machine
  
The dataset used in this project is a customer data set of a telecommunications provider, extracted from Kaggle (https://www.kaggle.com/competitions/customer-churn-prediction-2020/overview). The training data will be used to build the predictive models and to evaluate the best model, which will then be used to predict the test data.
The results of this project will be a set of predictive models that can be used to identify customers who are at risk of churn. The company can use these models to target these customers with retention campaigns or to offer them incentives to stay.
# 3. Data Dictionary

The training dataset contains 4250 samples. Each sample contains 19 features and 1 boolean variable "churn" which indicates the class of the sample. The 19 input features and 1 target variable are:

"state", string. 2-letter code of the US state of customer residence

"account_length", numerical. Number of months the customer has been with the current telco provider

"area_code", string="area_code_AAA" where AAA = 3 digit area code.

"international_plan", (yes/no). The customer has international plan.

"voice_mail_plan", (yes/no). The customer has voice mail plan.

"number_vmail_messages", numerical. Number of voice-mail messages.

"total_day_minutes", numerical. Total minutes of day calls.

"total_day_calls", numerical. Total minutes of day calls.

"total_day_charge", numerical. Total charge of day calls.

"total_eve_minutes", numerical. Total minutes of evening calls.

"total_eve_calls", numerical. Total number of evening calls.

"total_eve_charge", numerical. Total charge of evening calls.

"total_night_minutes", numerical. Total minutes of night calls.

"total_night_calls", numerical. Total number of night calls.

"total_night_charge", numerical. Total charge of night calls.

"total_intl_minutes", numerical. Total minutes of international calls.

"total_intl_calls", numerical. Total number of international calls.

"total_intl_charge", numerical. Total charge of international calls

"number_customer_service_calls", numerical. Number of calls to customer service

"churn", (yes/no). Customer churn - target variable.

# 4. Conclusion

The Support Vector Machine model performed the best, with an F1 score of 0.74 and an AUC score of 0.69. It also showed no signs of overfitting or underfitting. Therefore, the Support Vector Machine model was chosen as the best model for predicting customer churn.
