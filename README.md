# Mall Customer Data Cleaning & Preprocessing

This project demonstrates cleaning and preprocessing of the Mall Customer dataset. Key steps performed:

1. **Loaded dataset** (`mall.csv`) into a pandas DataFrame  
2. **Handled missing values** by filling numeric columns with mean and categorical (`gender`) with 'Unknown'  
3. **Removed duplicates** to avoid repeated records  
4. **Encoded categorical column** (`gender`) using one-hot encoding for machine learning compatibility  
5. **Detected and removed outliers** in numeric columns (`age`, `annual_income_(k$)`, `spending_score_(1-100)`) using the IQR method  
6. **Scaled numeric features** using `StandardScaler` so all numeric data are on the same scale  
7. **Saved the cleaned dataset** (`mall_cleaned.csv`) ready for analysis or ML

**Tech Stack:** Python, Pandas, Scikit-learn  

Hrithik Kumar  
Data Analyst
