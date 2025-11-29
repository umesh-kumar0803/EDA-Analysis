A concise Exploratory Data Analysis (EDA) project focused on understanding factors that influence loan default risk.
This analysis is based on two datasets: current loan applications and previous loan application history.
Key Objectives

Analyze borrower demographics and financial behavior

Identify patterns associated with payment difficulties (TARGET = 1)

Perform thorough data quality checks

Compare risk indicators across customer segments

Explore the influence of previous loan decisions on current default risk

What’s Inside

Missing Value Analysis – detection, visualization, and imputation

Outlier Detection using the IQR method

Univariate & Bivariate Analysis for numeric and categorical variables

Segmented Analysis comparing defaulters vs non-defaulters

Correlation Analysis split by TARGET

Previous Application Insights joined using SK_ID_CURR

All analysis is implemented in Python using Jupyter Notebook, leveraging Pandas, NumPy, Matplotlib, and Seaborn.

Files

loan_default_eda.ipynb – complete EDA workflow

application_data.csv – main dataset

previous_application.csv – historical applications

columns_description.csv – data dictionary

Summary of Findings

The dataset shows strong class imbalance (fewer defaulters).

Age, income, credit amount, and employment duration show clear differences between TARGET groups.

Previous loan outcomes (Refused, Canceled, Approved) strongly correlate with current behavior.

Data contains significant missing values and outliers, requiring preprocessing.

Author

Umesh Kumar
Data Analytics | Data Science Enthusiast
