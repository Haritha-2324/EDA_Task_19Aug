# Day 2 - Handling Missing Data

We identified missing values uisng 'df.isna().sum()'. Based on the extent, we used appropriate strategies like dropping rows or imputinh with mean/forward fill. Cleaned data is saved as  'sales_data_cleaned.csv'.

# Day 3 - Fix Data Types and Remove duplicates

Handled the datatypes of the entries present in the dataset using df.dtypes and convert the numeric and date columns. Saved the version of this file. Drop or removed the duplicate entries present in the dataset

# Day 4 - Feature Engineering

Choosing the proper features from the dataset for the prediction by it's various entries from rows and columns. Drop the unnecessary features and save the existing dataset. 

# Day 5 - Data Normalization & Scaling

Identified numerical columns in the dataset. Applied 'MinMaxScaler' to normalize values between 0 and 1. Saved the pre-processed dataset file

#  Day 6 - Export data for Power BI

Load the pre-processed data from the previous day task. Verified data integrity and structure.
Export the finalized dataset as "final_data_for_powerbi.csv" for visualization in PowerBI.

# Day 7 – Data Visualization Planning for Power BI 
 
To visualize sales performance across regions, products, and time periods using key metrics.
KPIs to Display - Total Revenue - Average Order Value - Revenue by Product Category - Sales Trend Over Time.

## Day 8 - Data Preprocessing Summary

Below are the steps performed during the preprocessing pipeline:

1. **Handled Missing Values (Day 3):**  
   - Used `isna().sum()` to identify missing values.  
   - Imputed missing numerical columns with mean.  
   - Filled missing categorical values with `'Unknown'`.  

2. **Fixed Data Types & Removed Duplicates (Day 4):**  
   - Converted date columns using `pd.to_datetime()`.  
   - Converted object columns to numeric types using `pd.to_numeric()`.  
   - Removed duplicate rows using `drop_duplicates()`.  

3. **Applied Feature Scaling (Day 5):**  
   - Applied `MinMaxScaler` from scikit-learn to normalize numeric features.  
   - Saved results as `preprocessed_data.csv`.  

4. **Exported Clean Data for Power BI (Day 6):**  
   - Verified final structure of data.  
   - Exported dataset for visualization as `final_data_for_powerbi.csv`.  

5. **Planned Visualizations (Day 7):**  
   - Identified key KPIs and suitable chart types.  
   - Documented layout in `visualization_plan.md`.

These steps ensure the dataset is clean, standardized, and ready for visualization and modeling.

# Day 9 - Power BI Data Connection

Loaded the dataset 'final_data_for_powerbi.csv' into Power BI. 
Verified the data model and field types. Saved the Power BI file as 'example.pbix'.


