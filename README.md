# Credit-Card-Default-Prediction
A machine learning model to predict credit card default risk based on customer behavior, transactions, and credit bureau data. Developed for Bank A as part of an IIT Bombay case study to enable risk-based management of existing credit card customers.
# Credit Card Behavior Score Prediction
### Overview
This project is part of a case study from IIT Bombay for Bank A, focused on developing a Behaviour Score for existing credit card customers. The Behaviour Score is a predictive model that estimates the probability of default for each customer, helping the bank manage credit risk more effectively.

The primary goal is to use historical data to build a machine learning model that predicts the likelihood of a customer defaulting on their credit card payments. This model can then be deployed for risk-based customer management and portfolio optimization.

### Project Objectives
- Build a robust predictive model using customer behavioural, transaction, and bureau data.
- Predict the probability of default (bad_flag) for each customer.
- Generate predictions on validation data.
- Provide detailed documentation and insights for stakeholders.

### Features & Functionality
- Preprocessing of structured financial data
- Handling of missing values and outliers
- Feature engineering and selection
- Model training using classification algorithms (e.g., Logistic Regression, Random Forest, XGBoost)
- Performance evaluation using AUC, log loss, and confusion matrix
- Prediction of default probabilities on unseen validation data
- Export of predictions in the required submission format

### Dataset Description
#### The dataset consists of two main files:
- Development Data: 96,806 credit card records with input features and the bad_flag (target variable).
- Validation Data: 41,792 credit card records with the same input features but without the target. Used for inference only.
- Data set links:-
- Dev_data_to_be_shared- Training dat
- validation_data_to_be_shared- Testing data
- my_dataframe- imputed data to fill training data(needed in code)
- my_results_xgb- results using xg boost classifier
- my_results_logistic- results using logistic regression
- my_results_randomforest- results using random forest

#### The features include:
- onus_attributes_*: On-us credit limit and usage behavior
- transaction_attribute_*: Transaction frequency and amounts
- bureau_*: Tradeline level credit history from bureaus
- bureau_enquiry_*: Credit enquiry data from bureaus

## Prerequisites
- Kaggle account
