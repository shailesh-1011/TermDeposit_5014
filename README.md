# Term Deposit Subscription Prediction

Welcome to the **Term Deposit Subscription Prediction** project! This repository contains all the resources related to predicting whether a customer will subscribe to a term deposit based on various features of a telephonic marketing campaign conducted by a Portuguese banking institution.

## Project Overview

Term deposits are a crucial source of income for banks. The goal of this project is to build a predictive model that can identify customers who are likely to subscribe to a term deposit. This helps in targeting the right customers and optimizing the marketing efforts.

### Data Description

The dataset used for this project is derived from direct marketing campaigns conducted through phone calls. The dataset includes two files:

- **train.csv**: Contains 40,000 rows and 17 columns.
- **test.csv**: Contains 5,211 rows and 16 columns.

#### Columns in the Dataset

1. **age**: Age of the client (numeric).
2. **job**: Type of job (categorical).
3. **marital**: Marital status (categorical).
4. **education**: Level of education (categorical).
5. **default**: Has credit in default? (binary).
6. **balance**: Average yearly balance in euros (numeric).
7. **housing**: Has a housing loan? (binary).
8. **loan**: Has a personal loan? (binary).
9. **contact**: Contact communication type (categorical).
10. **day**: Last contact day of the month (numeric).
11. **month**: Last contact month of year (categorical).
12. **duration**: Last contact duration in seconds (numeric).
13. **campaign**: Number of contacts performed during this campaign (numeric).
14. **pdays**: Days since the client was last contacted (numeric).
15. **previous**: Number of contacts performed before this campaign (numeric).
16. **poutcome**: Outcome of the previous marketing campaign (categorical).
17. **y**: Has the client subscribed to a term deposit? (binary, target variable).

### Tools Used

- **Python**: For data cleaning, preprocessing, and modeling.
- **Pandas**: For data manipulation.
- **NumPy**: For numerical computations.
- **Matplotlib** & **Seaborn**: For data visualization.
- **Power BI**: For creating interactive dashboards.
- **Streamlit**: For building web apps to showcase insights.

### Project Structure

- **data/**: Contains the train and test CSV files.
- **notebooks/**: Jupyter notebooks for data exploration and model development.
- **scripts/**: Python scripts for data preprocessing and modeling.
- **visualizations/**: Power BI dashboards and exported PDF reports.
- **readme.md**: Project documentation.

### Key Insights & Visualizations

- **Age Distribution**: Distribution of customers' ages.
- **Job Type Analysis**: Subscription rates across different job types.
- **Marital Status**: Impact of marital status on subscription.
- **Education Level**: Subscription rates by education level.
- **Contact Method**: Effectiveness of different contact methods.
- **Balance vs Subscription**: Relationship between balance and subscription.
- **Duration of Last Contact**: Impact of call duration on subscription likelihood.
- **Previous Campaign Outcome**: Influence of previous campaign outcomes on current subscriptions.


