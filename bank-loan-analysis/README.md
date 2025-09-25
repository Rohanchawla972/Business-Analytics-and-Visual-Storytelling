# Bank Loan Analysis

## Project Overview
This project focuses on the integration and analysis of bank loan applications using multiple data sources (CSV, XML, and JSON).  
The goal is to perform exploratory analysis, feature engineering, and structured reporting to extract actionable insights on customer behavior and loan risk factors.

## Repository Structure
- **README.md** — Project overview and documentation  
- **Bank_Loan_Analysis_Report.pdf** — Final detailed report with full analysis and recommendations  
- **Analysis of Bank Loan Applications.ipynb** — Python notebook with step-by-step data integration and analysis  
- **data/** — Raw datasets (`bank.txt`, `bank_extra.xml`, `bank_extra.json`)  

## Key Analysis and Insights
- **Customer Profiles**: The dataset contains 418 loan applications with 15 key attributes, including demographics, employment, savings/checking balances, and loan purpose.  
- **Financial Balances**: Created a `TotalBalance` metric combining savings and checking. The lowest balances were close to $0, while the top 15 lowest customers had only a $104 spread, indicating a narrow risk band.  
- **Application Trends**: Applications were distributed across months, with some loan purposes (e.g., car loans, appliances) recurring frequently. Each month supported multiple distinct loan purposes.  
- **Censored Purposes**: Customers with ≥3 years of residence often applied for loans in censored categories (e.g., car or appliance purchases).  
- **Demographic Insights**: Pivot tables showed how education level and job type correlated with average age and stability (years at residence).  

## Tools and Technologies
- **Languages**: Python (pandas, NumPy)  
- **Data Sources**: CSV, XML, JSON  
- **Environment**: Jupyter Notebook  

## Results
The analysis provided a structured understanding of loan applicants, helping identify low-balance customers, seasonal loan demand, and demographic patterns. These insights can inform risk assessment and targeted financial product strategies.

