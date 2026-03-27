# churn-data-cleaning-eda
Cleaning and visualizing a 594k row churn dataset. Fixing the mess before the modeling begins.

📄 Task 01: Data-Cleaning-EDA
Data-Cleaning-EDA

A systematic approach to transforming raw customer data into a model-ready dataset. Features automated outlier detection, missing value treatment, and multi-variable correlation analysis.

📊 Customer Data Preparation

Internship Project — IncodeVision

📝 Overview
This project focuses on the "messy" side of data science. Before any modeling could happen, I had to process 594k+ rows of raw customer records to ensure the final predictions wouldn't be skewed by noise or inconsistent formatting.

📊 Methodology

Data Collection: Worked with the provided IncodeVision training dataset.

Preprocessing: Fixed missing TotalCharges values, handled duplicates, and utilized the IQR method to neutralize extreme outliers in tenure and spending.

Feature Engineering: Standardized categorical variables (Contract type, Internet service) and scaled numerical features for consistency.

EDA: Created heatmaps and box plots to identify that high monthly charges and short tenure are the primary "red flags" for churn.

🛠️ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Google drive link - https://drive.google.com/drive/folders/1WWVQtFnF6FLxo5rCMRsQKqCYuL6hKL4L?usp=sharing

📈 Key Results

Dataset Status: 100% cleaned and validated.

Primary Insights: Identified a strong correlation between Month-to-Month contracts and immediate churn risk.
