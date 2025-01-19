Term Deposit Prediction - Bank Marketing Campaign
Project Overview
This project aims to predict whether a client of a Portuguese bank will subscribe to a term deposit based on their data from direct marketing campaigns. The dataset used for this project contains information about clients, their interactions with the bank's marketing campaigns, and the final outcome (whether they subscribed to a term deposit or not).

Dataset Description :
The data consists of two datasets:
train.csv: Contains 40,000 rows and 17 columns (for training).
test.csv: Contains 5,211 rows and 16 columns (for testing).



Columns in the Dataset:
age: Age of the client (numeric)
job: Type of job (categorical)
marital: Marital status (categorical)
education: Level of education (categorical)
default: Whether the client has credit in default (binary)
balance: Average yearly balance in euros (numeric)
housing: Whether the client has a housing loan (binary)
loan: Whether the client has a personal loan (binary)
contact: Type of contact communication (categorical)
day: Last contact day of the month (numeric)
month: Last contact month of the year (categorical)
duration: Duration of the last contact (numeric)
campaign: Number of contacts performed during this campaign (numeric)
pdays: Number of days since the client was last contacted in a previous campaign (numeric)
previous: Number of contacts before this campaign (numeric)
poutcome: Outcome of the previous marketing campaign (categorical)
y: Outcome variable indicating whether the client subscribed to a term deposit (binary)



Tools Used :
Python: For data cleaning, preprocessing, and modeling.
Pandas: For data manipulation.
NumPy: For numerical computations.
Matplotlib &  Seaborn: For data visualization.
Power BI: For creating interactive dashboards.
Streamlit: For building web apps to showcase insights.


Project Structure
data/: Contains the train and test CSV files.
notebooks/: Jupyter notebooks for data exploration and model development.
scripts/: Python scripts for data preprocessing and modeling.
visualizations/: Power BI dashboards and exported PDF reports.
readme.md: Project documentation.



Key Insights & Visualizations
Age Distribution: Distribution of customers' ages.
Job Type Analysis: Subscription rates across different job types.
Marital Status: Impact of marital status on subscription.
Education Level: Subscription rates by education level.
Contact Method: Effectiveness of different contact methods.
Balance vs Subscription: Relationship between balance and subscription.
Duration of Last Contact: Impact of call duration on subscription likelihood.
Previous Campaign Outcome: Influence of previous campaign outcomes on current subscriptions.
