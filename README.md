# Insurance Data Cleaning & Preparation

This project focuses on **data cleaning and preprocessing** of a health insurance claims dataset.  
The goal is to ensure data quality and readiness for further analysis or predictive modeling.

---

## Project Overview

The dataset (`health_insurance_claims.csv`) contains claim records from a simulated health insurance system.  
Through this project, I performed key data preparation steps such as:

- Identifying and handling missing values  
- Detecting and removing duplicate records  
- Handling outliers in numerical data  
- Encoding categorical variables  
- Normalizing numeric features  

Each decision in the cleaning process was based on data characteristics and best practices in data preprocessing.

---

## Key Steps

### 1. Initial Data Inspection
- Loaded and explored the dataset to understand its structure  
- Checked data types, summary statistics, and variable distributions  

### 2. Handling Missing Values
- Replaced missing values using appropriate methods:
  - **Age:** Median imputation  
  - **Claim Amount:** Mean/Median (based on distribution)  
  - **Diagnosis Code:** Mode (most frequent value)  
- Compared missing data before and after cleaning  

### 3. Duplicate & Data Integrity Checks
- Detected and removed duplicate `claim_id` entries  
- Ensured all remaining claim IDs were unique  

### 4. Outlier Detection & Treatment
- Used **IQR method** to identify outliers in `claim_amount`  
- Visualized with boxplots and histograms  
- Decided between capping or transforming extreme values  

### 5. Data Transformation
- Encoded categorical variables (`gender`, `policy_type`, `payment_status`)  
- Standardized and normalized numeric variables  
- Prepared data for further statistical or machine learning use  

---

## Skills & Tools Used
- **Python:** pandas, numpy, matplotlib, seaborn  
- **Techniques:** Missing value imputation, outlier handling, data normalization, encoding  
- **Concepts:** Data quality, feature engineering, EDA  

---

## Files in Repository
| File | Description |
|------|--------------|
| `Fiore Aurora Oei Assignment 1.ipynb` | Main Jupyter Notebook containing full analysis |
| `health_insurance_claims.csv` | Original dataset used in the project |
| `.gitignore` | List of files/folders ignored in version control |
| `README.md` | Project documentation (this file) |

---

⭐ **Created as part of an applied data analysis project on health insurance claims.**
