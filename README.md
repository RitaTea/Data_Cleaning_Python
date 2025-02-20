# Healthcare Data Cleaning & Analysis Project 


This project focused on **cleaning, analyzing, and extracting insights** from a messy healthcare dataset. The dataset contains inconsistencies such as:
 **Duplicate IDs**
 **Mixed-case names**
 **Missing values in Age, Blood Type, Education, and Health Condition**
 **Negative values in Salary**
 **Non-numeric Credit Score values**
 **Incorrect Date formats**
  **City names with inconsistent capitalization**

The project also includes **advanced analysis**, such as:
- Outlier detection
- Correlation analysis
- Data visualization
- Predictive modeling (Salary prediction & Health Condition classification)
- Clustering analysis



##  Steps for Data Cleaning

1. **I converted all names to uppercase first, then lowercase.**
2. **I ensured city names have proper capitalization** (first letter uppercase, rest lowercase).
3. **I filled missing values in Age, Blood Type, and Education using statistical imputation.**
4. **I fixed negative salary values by taking their absolute value.**
5. **I replaced 'N/A' values in Credit Score with the mean score and ensure it's numeric.**
6. **I formated the Date column properly using pandas `to_datetime()`.**
7. **I removed duplicate records based on unique IDs.**
8. **I handled missing values in Health Condition appropriately.**
9. **I standardized categorical variables using One-Hot Encoding.**
10. **I Normalized numerical columns (e.g., Salary, Credit Score) for better analysis.**



After cleaning, i performed **Exploratory Data Analysis** using **Seaborn & Matplotlib**:

 **Salary Distribution** – Histogram to show income trends.  
 **Age Distribution** – Visualizing the age group distribution.  
 **Credit Score vs Salary** – Scatter plot to analyze credit behavior.  
 **Health Condition Count** – Bar chart of different health conditions. 





