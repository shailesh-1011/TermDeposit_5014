# Term Deposit Subscription Prediction

## Introduction

This project focuses on predicting whether clients will subscribe to a term deposit based on data from telephonic marketing campaigns conducted by a Portuguese banking institution. The goal is to develop a predictive model that identifies clients most likely to subscribe, thereby optimizing marketing efforts and reducing costs.

## Project Overview

### Problem Statement

Term deposits are a significant source of income for banks. Telephonic marketing campaigns, while effective, require substantial investment. Our aim is to build a predictive model that helps identify clients who are most likely to subscribe to a term deposit, ensuring a targeted and cost-efficient approach.

### Objective

The objective is to predict if a client will subscribe to a term deposit using various client and campaign-related features. By accurately predicting client behavior, banks can optimize their telephonic marketing campaigns and allocate resources more effectively.

## Data Description

The dataset consists of data related to telephonic marketing campaigns of a Portuguese banking institution. It includes information on clients, campaign details, and previous campaign outcomes. The data is divided into training and test sets:

- **Training Set**: 40,000 rows and 17 columns
- **Test Set**: 5,211 rows and 16 columns (without target variable)

### Column Descriptions

1. **Client Data**:
   - `age`: Age of the client (numeric)
   - `job`: Type of job (categorical)
   - `marital`: Marital status (categorical)
   - `education`: Education level (categorical)
   - `default`: Credit in default (binary)
   - `balance`: Average yearly balance in euros (numeric)
   - `housing`: Housing loan (binary)
   - `loan`: Personal loan (binary)

2. **Last Contact of Campaign**:
   - `contact`: Contact communication type (categorical)
   - `day`: Last contact day of the month (numeric)
   - `month`: Last contact month of the year (categorical)
   - `duration`: Last contact duration in seconds (numeric)

3. **Other Attributes**:
   - `campaign`: Number of contacts performed during this campaign (numeric)
   - `pdays`: Number of days since the client was last contacted from a previous campaign (numeric)
   - `previous`: Number of contacts performed before this campaign (numeric)
   - `poutcome`: Outcome of the previous marketing campaign (categorical)

4. **Target**:
   - `y`: Has the client subscribed to a term deposit? (binary)

## Approach

### Data Preprocessing

1. Handling missing values
2. Encoding categorical variables
3. Scaling numerical features
4. Removing outliers
5. Handling imbalanced data using SMOTE

### Feature Engineering

1. Creating polynomial features
2. Interaction terms between features

### Model Selection

We chose Logistic Regression for its simplicity, efficiency, and interpretability. It is ideal for binary classification tasks and provides clear insights into feature importance. 

### Hyperparameter Tuning

Used GridSearchCV to find the best parameters for the model, ensuring optimal performance.

## Model Evaluation

The model was evaluated using the following metrics:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **ROC-AUC Score**

## Results

- **Best Parameters**: 'C': 0.1, 'max_iter': 100, 'penalty': 'l1', 'solver': 'saga'
- **Validation Accuracy**: 0.83
- **Validation F1 Score**: 0.83

## Screenshots

#### Home Page
![Home Page](https://github.com/shailesh-1011/TermDeposit_5014/blob/main/Logos/HomePage.png)

#### Dashboard Page 1
![Page 1](https://github.com/shailesh-1011/TermDeposit_5014/blob/main/Logos/Page%201.png)

#### Dashboard Page 2
![Page 2](https://github.com/shailesh-1011/TermDeposit_5014/blob/main/Logos/Page%202.png)


## Conclusion

In conclusion, our project successfully leveraged Logistic Regression to enhance telephonic marketing campaigns for term deposit subscriptions. By identifying clients most likely to subscribe, we optimized marketing efforts and reduced costs. The model's simplicity and interpretability make it a valuable tool for banks to make data-driven decisions.

## Authors

- Shailesh Kumar Singh
- Anand Nair
- Prashant Patil


