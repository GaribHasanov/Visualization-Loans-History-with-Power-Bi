# Visualization – Loans History with Power BI

## Project Overview
This project is a **Power BI data visualization solution** for analyzing historical loan data, including both loan disbursement and repayment activities.

The main goal is to transform raw financial data into interactive dashboards that provide clear insights into loan performance, repayment behavior, and financial trends.

---

## Business Objective
The project helps to:

- Analyze total loan disbursement
- Track repayment performance over time
- Compare issued loans vs recovered amounts
- Provide visual insights for financial decision-making

---

## Dataset Workflow

The project includes the following steps:

- Data import from Excel source
- Data transformation in Power Query
- Creation of calculated measures
- Dashboard development in Power BI

---

## Page 1: Disbursed Loans Dashboard

This page focuses on analyzing all disbursed loans and their distribution patterns.

Key insights:
- Total loan amount disbursed
- Loan distribution trends
- Borrower analysis

![Disbursed Loans](https://user-images.githubusercontent.com/60735401/134350504-b6d9550b-4f57-4418-9f95-b238b34089c2.PNG)

---

## Page 2: Received Repayment Dashboard

This page provides insights into loan repayments and financial inflows.

Key insights:
- Total repayments received
- Repayment trends over time
- Comparison between disbursed vs repaid amounts

![Received Repayment](https://user-images.githubusercontent.com/60735401/134350909-a542e672-4e3b-48e8-a9d1-15d6e2ad1621.PNG)

---

## Data Connection & Refresh Setup

The project also includes data connection setup and refresh configuration.

Steps:
- Import Excel file as data source
- Create a blank query to track last refresh date
- Use custom M query for refresh monitoring

### Data Source Setup

![Add excel file from the source](https://user-images.githubusercontent.com/60735401/134138150-2d198d3d-314e-44d9-bdec-de4d8df67186.PNG)

---

### Refresh Tracking (Blank Query)

![Blank query_1](https://user-images.githubusercontent.com/60735401/134138269-40f0672a-82db-4d05-964b-d53dc3d1b5c7.PNG)

---

### Refresh Query Reference

![Blank query_2](https://user-images.githubusercontent.com/60735401/134138323-e251a0cd-3b37-4a87-b2ea-0520e31f2b3e.PNG)

Reference:
https://github.com/GaribHasanov/POWER-BI-Projects/blob/main/Loans%20History/Sources%20etc/Refresh-blank-query.txt

---

## Tools Used

- Power BI
- Power Query (M Language)
- Excel Data Source
- Data Visualization

---

## Key Insights

- Loan disbursement trends over time
- Repayment performance tracking
- Financial inflow vs outflow comparison
- Data-driven decision support

---

## Conclusion

This project demonstrates how Power BI can be used to convert raw loan data into meaningful dashboards, enabling better financial analysis and decision-making through interactive visual storytelling.
