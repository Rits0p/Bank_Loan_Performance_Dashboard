# 🏦 Bank Loan Performance Dashboard | Power BI + SQL Project

A comprehensive business intelligence solution built using Power BI, SQL, and Power Query, this interactive dashboard provides deep insights into bank loan applications, funding trends, repayment performance, and borrower profiles across multiple dimensions. It’s designed to support financial analysts, credit officers, and decision-makers in evaluating loan health and operational efficiency.

---

## 📌 Project Overview

The objective of this project was to analyze and visualize bank loan data to uncover patterns in loan issuance, repayment behavior, and risk segmentation. The dashboard is structured into three core sections:

- **Summary View**: High-level metrics on total applications, funded amounts, interest rates, and DTI ratios  
- **Overview Analysis**: Geographic, demographic, and categorical breakdowns of loan performance  
- **Detailed Insights**: Row-level data exploration with filters for loan status, borrower attributes, and financial indicators  

Data was cleaned and modeled using Power BI Power Query, while SQL was used to validate joins, perform aggregations, and ensure data integrity before dashboard development.

---

## 💡 My Journey & Experience

The raw dataset included thousands of loan records with varying formats and missing values. Here's how I approached the challenge:

### Power Query Operations
- Removed nulls and duplicates  
- Standardized data types (e.g., currency, percentages)  
- Created relationships for dimensional modeling  

### SQL Validation
- Verified joins between borrower, loan, and repayment tables  
- Cross-checked totals and averages for interest rate and DTI  
- Ran test queries to validate monthly and state-level aggregations  

The dashboard design was fully custom — no templates used. Every chart, slicer, and layout element was crafted to maximize clarity and usability for financial decision-making.

---

## 🧰 Tools & Techniques Used

- **Power BI**: For dashboard creation and interactive visualizations  
- **Power Query**: For data cleaning, transformation, and modeling  
- **SQL**: For backend validation, joins, and logic verification  
- **DAX**: For calculating KPIs like average interest rate, DTI, and loan health ratios  
- **Custom Visuals**: Pie charts, bar graphs, maps, and tables for multidimensional analysis  
- **Slicers & Filters**: Loan status, state, grade, purpose, and ownership type  

---

## 📊 Dashboard Sections & Highlights

### 🔹 1. Summary View
- **Total Loan Applications**: 38.6K  
- **Total Funded Amount**: $435.8M  
- **Total Loan Issued**: $473.1M  
- **Average Interest Rate**: 12.0%  
- **Average DTI**: 13.3%  
- **Good vs Bad Loan Ratio**: 86.2% vs 13.8%  

### 🔹 2. Overview Analysis
- **Monthly Trends**: Loan recovery tracked across Jan–Dec  
- **State-Level Distribution**: Heatmap of loan amounts across U.S. states  
- **Loan Term Breakdown**: 36 vs 60 months  
- **Employment Duration Impact**: Loan performance by borrower job tenure  
- **Loan Purpose Analysis**: Debt consolidation, credit card, home improvement, etc.  
- **Home Ownership Comparison**: Mortgage vs Rent vs Own  

### 🔹 3. Detailed Insights
- **Loan-Level Table**: Includes ID, purpose, grade, state, funded & received amounts, interest rate, DTI, income, recovery, and days past due  
- **Loan Status Breakdown**: Current, Charged Off, Fully Paid  
- **MTD & MTM Metrics**: Month-to-date and month-to-month comparisons for funding and rejection  

---

## 🚀 Key Insights Gained

- Good loans dominate the portfolio, indicating strong underwriting standards  
- California leads in both volume and repayment success  
- Interest rates and DTI remain consistent across statuses, suggesting stable lending criteria  
- Employment length and home ownership show strong correlation with repayment behavior  
- Loan purpose significantly affects recovery rates — credit card and debt consolidation perform best  

---

## 📝 Notes

- Entire dashboard built manually from scratch — no templates used  
- Power BI Power Query handled all data transformation (no Excel involved)  
- SQL used extensively for backend logic and validation  
- Visuals reflect real-world financial reporting standards  
- Ideal for use by credit analysts, loan officers, and financial strategists

  ## Snapshots Of Dashboards
 <img width="1052" height="602" alt="Snapshot of Detail Dashbaord" src="https://github.com/user-attachments/assets/bbfd7ea3-c052-4c54-be58-ae3fb8e9a3d9" />
 <img width="1047" height="601" alt="Snapshot of Overview Dashbaord" src="https://github.com/user-attachments/assets/ff83e071-b1e3-4023-bac4-40a1a7d8a075" />
 <img width="1047" height="603" alt="Snapshot of Summary Dashbaord" src="https://github.com/user-attachments/assets/e425bb01-c305-4be0-8ff1-6058524af76b" />


