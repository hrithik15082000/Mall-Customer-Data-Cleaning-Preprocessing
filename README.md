# Mall Customer Data Cleaning & Preprocessing

## Steps Performed
1. **Loaded dataset (`mall.csv`) into a pandas DataFrame**  
   Imported the dataset using pandas for further cleaning and preprocessing.

2. **Handled missing values**  
   Filled missing values in numeric columns (`age`, `annual_income_(k$)`, `spending_score_(1-100)`) with their mean, and replaced missing values in the categorical column (`gender`) with 'Unknown'.

3. **Removed duplicates**  
   Checked for and removed duplicate records to ensure data consistency and avoid biased analysis.

4. **Encoded categorical column (`gender`) using one-hot encoding**  
   Converted categorical values (`Male`, `Female`, `Unknown`) into separate binary columns, making the data machine learning compatible.

5. **Detected and removed outliers using the IQR method**  
   Identified extreme values in numeric columns (`age`, `annual_income_(k$)`, `spending_score_(1-100)`) using the Interquartile Range (IQR) technique and removed them to maintain data quality.

6. **Scaled numeric features using StandardScaler**  
   Standardized numeric features so that all values lie on a common scale, improving model performance in ML algorithms.

7. **Saved the cleaned dataset (`mall_cleaned.csv`)**  
   Exported the final cleaned and preprocessed dataset for further analysis, visualization, or machine learning tasks.

## Summary
The dataset was thoroughly cleaned by handling missing values, removing duplicates, encoding categorical data, and eliminating outliers using the IQR method. Numeric features were then standardized with `StandardScaler` to ensure consistency. Finally, the cleaned dataset was saved as `mall_cleaned.csv`, making it ready for analysis, visualization, and machine learning applications.

---

Hrithik Kumar  
Data Analyst
