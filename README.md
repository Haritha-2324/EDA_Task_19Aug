# Handling Missing Data

We identified missing values uisng 'df.isna().sum()'. Based on the extent, we used appropriate strategies like dropping rows or imputinh with mean/forward fill. Cleaned data is saved as  'sales_data_cleaned.csv'.

# Fix Data Types and Remove duplicates

Handled the datatypes of the entries present in the dataset using df.dtypes and convert the numeric and date columns. Saved the version of this file. Drop or removed the duplicate entries present in the dataset

# Feature Engineering

Choosing the proper features from the dataset for the prediction by it's various entries from rows and columns. Drop the unnecessary features and save the existing dataset. 

# Data Normalization & Scaling

Identified numerical columns in the dataset. Applied 'MinMaxScaler' to normalize values between 0 and 1. Saved the pre-processed dataset file

# Export data from Power BI

Load the pre-processed data from the previous day task. Verified data integrity and structure.
Export the finalized dataset as "final_data_for_powerbi.csv" for visualization in PowerBI.



