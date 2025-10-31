# Ecommerce_Analysis    
   
# E-commerce Customer Analytics: Online Retail Dataset 
   ist
## 📌 Project Overview     
This project performs **Exploratory Data Analysis (EDA) and Customer Segmentation** on the Online Retail dataset, which contains transactional data for a UK-based online retail store. The objective is to extract actionable business insights, analyze customer behavior, and prepare the dataset for potential predictive modeling.
    
  
## 🗂 Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail)  
- **Rows:** ~541,909  
- **Columns:** 8 (`InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, `Country`)  
- **Description:** Each row represents a transaction, including product purchased, quantity, customer, and country.


## 🎯 Project Objectives
1. **Exploratory Data Analysis (EDA)**
   - Understand dataset structure, types, and missing values.
   - Analyze sales trends by country, month, and product.
   - Detect anomalies and outliers (e.g., negative quantities, returns).
   
2. **Customer Segmentation**
   - Compute **RFM metrics** (Recency, Frequency, Monetary) per customer.
   - Cluster customers into segments (VIPs, loyal, at-risk, churn-risk) using KMeans.
   
3. **Additional Analyses**
   - Identify top-selling products and revenue contributors.
   - Optional: Market basket analysis using association rules.
   - Optional: Monthly sales forecasting.



## 🛠 Tools & Technologies
- **Programming Language:** Python 3.x  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, openpyxl  
- **Environment:** Jupyter Notebook 



## 📁 Project Structure
Ecommerce_Analysis/
│
├── data/ 
│ └── Online_Retail.xlsx
├── notebooks/
│ └── EDA_Analysis.ipynb
├── scripts/ 
│ ├── data_prep.py
│ ├── analysis.py
│ └── utils.py
├── models/ 
├── README.md

this is update where i completed eda on the dataset

