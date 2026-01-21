# Multi-Source Financial Reconciliation

## 📌 Project Overview
This project implements an end-to-end financial reconciliation process by integrating transaction data from multiple sources—ERP exports and bank statements. The goal is to identify matched and unmatched transactions and provide a clear reconciliation summary using industry-standard tools.

---

## 🛠️ Technologies Used
- **MS SQL Server** – Data staging, ETL, and reconciliation logic  
- **Microsoft Excel** – Source CSV files and spot-check validation  
- **Tableau** – Visualization of reconciliation results  

---

## 📂 Data Sources
- **ERP Transactions CSV**
  - Transaction ID
  - Transaction Date
  - Amount
  - Reference Number

- **Bank Statement CSV**
  - Bank Transaction ID
  - Bank Date
  - Amount
  - Reference Number

---

## 🔄 ETL & Reconciliation Process
1. Imported ERP and Bank CSV files into SQL Server staging tables.
2. Validated data types and cleaned records where required.
3. Applied reconciliation logic using SQL JOINs on reference number and amount.
4. Classified transactions as **Matched** or **Unmatched**.
5. Generated a final reconciliation result table.

---

## 📊 Analysis & Visualization
- Reconciliation results were validated using Excel.
- A summary visualization was created in Tableau to compare matched vs unmatched transactions for quick analysis.

---

## ✅ Key Outcomes
- Successful integration of multi-source financial data
- Clear identification of mismatched transactions
- Professional, decision-ready reconciliation output

---

## ⏱️ Project Duration
**4 Days**

---

## 📌 Conclusion
This project demonstrates a real-world financial reconciliation workflow using SQL-based ETL and modern visualization tools. It reflects practical data validation, reconciliation logic, and reporting techniques commonly used in enterprise financial systems.
