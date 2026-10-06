# Customer Churn Prediction using Logistic Regression (Classification)

## Project Overview
This project uses Machine Learning to predict whether a customer is likely to leave a company based on customer information, services, contract type, and billing details.

## Tools & Libraries
* Python
* Pandas
* Matplotlib
* Scikit-learn

## Project Workflow:

### 1. Data Exploration & Cleaning
* Explored dataset structure and statistics.
* Analyzed churn distribution.
* Checked missing values and duplicates.
* Converted `TotalCharges` to numeric and handled missing values using the median.

### 2. Data Preprocessing
* Split the data into training (80%) and testing (20%) sets.
* Used `StandardScaler` for numerical features.
* Used `OneHotEncoder` for categorical features.
* Applied transformations using `ColumnTransformer`.
* 
### 3. Model Training & Evaluation
* Trained a Logistic Regression model.
* Evaluated performance using Accuracy, Confusion Matrix, Precision, Recall, and F1-score.

### 4. Customer Prediction
* Predicted churn for a new customer.
* Estimated the probability of churn using `predict_proba()`.

## Conclusion
This project demonstrates an end-to-end classification workflow, from data cleaning and preprocessing to model evaluation and customer churn prediction.
