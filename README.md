# neurofive ml track task 6
# Customer Churn Prediction

A machine learning project that predicts whether a telecom customer is likely to leave the company's services.

## Project Overview

Customer churn is an important business problem in industries such as telecommunications, banking, and SaaS. This project analyzes the Telco Customer Churn dataset to identify factors associated with customer churn and builds machine learning models to predict which customers are likely to leave.

## Objectives

- Perform Exploratory Data Analysis (EDA)
- Analyze factors related to customer churn
- Handle missing values and categorical variables
- Train a Decision Tree Classifier
- Train a Logistic Regression model
- Compare the performance of both models
- Identify the top features driving customer churn
- Provide a business-focused summary of the findings

## Dataset

**Telco Customer Churn Dataset**

The dataset contains customer information such as:

- Customer tenure
- Contract type
- Monthly charges
- Total charges
- Internet services
- Payment methods
- Customer churn status

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Machine Learning Models

### Decision Tree Classifier

A Decision Tree model was used because it is easy to interpret and helps identify which features are most important for predicting customer churn.

### Logistic Regression

A Logistic Regression model was trained as a baseline model and compared with the Decision Tree Classifier.

## Project Workflow

1. Load the Telco Customer Churn dataset
2. Perform quick exploratory data analysis
3. Clean and preprocess the data
4. Handle categorical variables using One-Hot Encoding
5. Split the dataset into training and testing data
6. Train Decision Tree and Logistic Regression models
7. Evaluate and compare both models
8. Identify the top features driving churn
9. Generate business insights

## Key Considerations

The dataset contains a class imbalance because the number of customers who churn is smaller than the number of customers who do not churn. This was considered during model training by using class balancing.

Model performance was evaluated using accuracy, classification reports, and confusion matrices.

## Business Value

Customer churn prediction can help businesses identify customers who may leave before they actually do. Companies can use these insights to improve customer retention through personalized offers, better service, improved contracts, or targeted customer support.

## Author

**Laiba Nasir**

AI Intern | Engineering Student

