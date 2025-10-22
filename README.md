# Bank-Loan-Portfolio-Analysis

**Objective**

To analyze loan application data and develop a KPI-driven dashboard that tracks key financial metrics, evaluates borrower performance, and provides insights into credit risk, funding trends, and repayment behavior.
The goal is to help financial stakeholders identify patterns in lending efficiency, optimize loan approvals, and monitor repayment performance over time.

**Process**
Imported the dataset financial_loan.csv containing 38,600 loan records with borrower details, funded amount, loan purpose, interest rate, DTI, and loan status.

Data Cleaning & Preparation (SQL):

Removed duplicates and handled missing values.

Validated data consistency (loan IDs, issue dates, funded vs received amounts).

Categorized loans into Good Loans (Fully Paid, Current) and Bad Loans (Charged Off) for risk segmentation.

Data Modeling (Power BI / Excel):

Connected cleaned dataset to Power BI and created calculated measures for key KPIs:

Total Loan Applications

Total Funded Amount

Total Amount Received

Average Interest Rate

Average DTI

Good Loan % vs Bad Loan %

MTD & MoM Performance Tracking

Dashboard Development:

Designed an interactive dashboard with cards, charts, and slicers for easy navigation.

Visualized trends by issue date, loan purpose, loan term, and state/region.

Added comparison sections for MTD vs PMTD metrics and Good vs Bad loan analysis.
