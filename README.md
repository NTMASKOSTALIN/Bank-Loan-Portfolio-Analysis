# Bank-Loan-Portfolio-Analysis

**Objective**

To analyze loan application data and develop a KPI-driven dashboard that tracks key financial metrics, evaluates borrower performance, and provides insights into credit risk, funding trends, and repayment behavior.
The goal is to help financial stakeholders identify patterns in lending efficiency, optimize loan approvals, and monitor repayment performance over time.

**Dataset & Tableau Dashboard**

- <a href="https://github.com/NTMASKOSTALIN/Bank-Loan-Portfolio-Analysis/blob/main/financial_loan.csv"> Bank Loan CSV file
- <a href="https://public.tableau.com/app/profile/masko.stalin.n.t/viz/BankLoanDashboard_17601235843910/Summary"> Tableau Dashboard

**KPIs:**

**Overall Performance Metrics**

Total Loan Applications — Total number of loan applications received.
Total Funded Amount — Total dollar value of loans funded.
Total Amount Received — Total repayments or payments collected from borrowers.

**Time-Based KPIs**

MTD (Month-To-Date) Loan Applications
PMTD (Previous Month-To-Date) Loan Applications
MTD Total Funded Amount
PMTD Total Funded Amount
MTD Total Amount Received
PMTD Total Amount Received
MTD Average Interest Rate
PMTD Average Interest Rate
MTD Average DTI (Debt-to-Income Ratio)
PMTD Average DTI
(These help track month-over-month performance changes.)

**Financial Health Metrics**

Average Interest Rate — Mean interest rate across all funded loans.
Average DTI (Debt-to-Income Ratio) — Average borrower income-to-debt ratio, indicating repayment capacity.

**Good Loan Analysis**

Good Loan Percentage — % of loans that are fully paid or currently active.
Good Loan Applications — Count of performing loans.
Good Loan Funded Amount — Total amount funded for performing loans.
Good Loan Received Amount — Total payments received from performing loans.

**Bad Loan Analysis**

Bad Loan Percentage — % of loans charged off or in default.
Bad Loan Applications — Count of non-performing loans.
Bad Loan Funded Amount — Total amount funded for defaulted loans.
Bad Loan Received Amount — Total payments received from bad loans (partial recoveries).

**Trend & Segmentation Metrics**

Loan Status Overview — Distribution across Fully Paid, Current, and Charged Off.
Monthly Trends by Issue Date — Month-wise funding and repayment trends.
Regional Analysis by State — Loan distribution and performance by borrower state.
Loan Term Analysis — Loan count and performance across different terms (e.g., 36 vs 60 months).
Loan Purpose Breakdown — Loan distribution by purpose (Debt Consolidation, Home Improvement, etc.).
Home Ownership Analysis — Performance segmentation by borrower home ownership status.

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
