# Data_science_project
# Customer Churn Analysis – Telecom Industry

## Project Overview

This project focuses on analyzing customer churn in the telecommunications industry using the IBM Telco Customer Churn dataset.

Customer churn refers to customers discontinuing a company's services. Understanding customer behavior and identifying patterns associated with churn can help businesses improve customer retention and make better business decisions.

The main objective of this project is to explore customer data, clean and preprocess the dataset, perform Exploratory Data Analysis (EDA), and derive meaningful business insights using Python.

## Business Problem

Customer churn is an important challenge for telecom companies because losing customers can affect revenue and long-term business growth.

Through this project, I aim to answer questions such as:

- Which customer groups have higher churn rates?
- Which contract type is associated with the highest churn?
- Do customers with shorter tenure churn more frequently?
- Which payment methods are associated with higher churn?
- What monthly charges are associated with churned customers?
- Which services are commonly used by customers who stay?

## Dataset

**Dataset:** IBM Telco Customer Churn

- Total records: 7,043 customers
- Total columns: 21
- Target variable: `Churn`
- Target categories: `Yes` and `No`

**Dataset source:**  
[IBM Telco Customer Churn Dataset](https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv)

The dataset contains customer demographics, account information, subscribed services, contract details, payment methods, monthly charges, total charges, and churn status.

## Technologies and Libraries Used

- **Python** – Programming and data analysis
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization

## Project Workflow

### 1. Data Collection and Understanding
- Collected the IBM Telco Customer Churn dataset.
- Examined dataset dimensions and column names.
- Inspected data types and statistical summaries.
- Understood the target variable and dataset structure.

### 2. Data Cleaning and Preprocessing
- Checked for missing values.
- Identified and handled duplicate records.
- Corrected inappropriate data types.
- Converted `TotalCharges` into a numerical format.
- Handled blank values.
- Prepared the dataset for further analysis.

### 3. Exploratory Data Analysis (EDA)
Performed exploratory analysis to identify patterns and relationships in customer data.

Analysis included:
- Customer churn distribution.
- Customer tenure analysis.
- Monthly and total charges distribution.
- Churn across different contract types.
- Churn by payment method.
- Customer demographics and churn.
- Relationships between numerical variables.

Created visualizations to make the findings easier to understand.

### 4. Business Insights

Used Pandas and NumPy to investigate important business questions, including:

- Customer groups with higher churn rates.
- Contract types associated with higher churn.
- The relationship between customer tenure and churn.
- Payment methods associated with customer churn.
- Monthly charges associated with churned customers.
- Service usage among retained customers.

The analysis helps identify customer segments that may require greater attention from customer retention teams.

## Key Learnings

Through this project, I gained practical experience in:

- Working with real-world datasets.
- Data cleaning and preprocessing.
- Handling missing values and incorrect data types.
- Performing exploratory data analysis.
- Using Pandas for grouping, aggregation, and analysis.
- Applying NumPy for numerical calculations.
- Creating meaningful data visualizations.
- Translating analytical findings into business insights.

## Future Improvements

I plan to extend this project by adding:

- Feature engineering.
- Statistical hypothesis testing.
- Machine learning models for churn prediction.
- Model evaluation and comparison.
- SQL-based business analysis.
- An interactive dashboard using Streamlit or Power BI.

## Conclusion

This project helped me understand how raw customer data can be transformed into meaningful business insights.

By combining data cleaning, exploratory analysis, and business-focused investigation, the project demonstrates the importance of data analytics in understanding customer behavior and supporting customer retention strategies.

---

**Project Category:** Data Analytics  
**Domain:** Telecommunications  
**Status:** Data Cleaning, Preprocessing, EDA, and Business Insights Completed
