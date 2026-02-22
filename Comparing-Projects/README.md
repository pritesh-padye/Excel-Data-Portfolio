# Excel Data Comparison & Reconciliation Projects

This repository contains three practical Excel-based data comparison and reconciliation projects.

Each project demonstrates how business datasets from different sources can be compared using structured formula logic to identify mismatches, missing records, and classification outcomes.

All solutions are built using Excel formulas without VBA, Power Query, or external tools.

---

## 📌 Projects Included

### 1️⃣ SAP vs Warehouse Data Comparison

Objective:
Compare SAP transaction data with Warehouse records to identify transactions that are not posted in SAP.

Key Logic:
- XLOOKUP used to check Order_ID presence
- If found → return Order_ID
- If not found → return "Not_Posted"

Business Use Case:
ERP reconciliation, transaction validation, audit checks.

---

### 2️⃣ GSTR2 Reconciliation (Tally vs GST Portal)

Objective:
Reconcile purchase invoice data between Tally and GST Portal.

Key Features:
- VSTACK used to combine datasets
- COUNTIFS used for duplicate detection
- IF logic for value mismatch detection
- Reconciliation_Status classification
- Difference_Check showing financial impact
- Pivot table summary for reporting

Business Use Case:
GST compliance, audit preparation, vendor reconciliation.

---

### 3️⃣ New vs Existing Customer Identification

Objective:
Identify new customers from Sales_Data by comparing with Old_Customer_List.

Key Logic:
- XLOOKUP used for customer comparison
- If found → return Customer Name
- If not found → return "New_Customer"

Business Use Case:
Customer acquisition tracking, CRM validation, marketing analysis.

---

## 🧠 Excel Functions Used Across Projects

- XLOOKUP  
- VSTACK  
- IF  
- COUNTIFS  
- Conditional Formatting  
- Pivot Tables  

---

## 💼 Skills Demonstrated

- Data reconciliation
- Cross-sheet comparison
- Duplicate detection
- Financial mismatch identification
- Status classification logic
- Formula-based automation
- Structured reporting using Pivot Tables

---

## ⚙️ Design Philosophy

✔ 100% Formula-Based  
✔ No VBA / Macros  
✔ No Power Query  
✔ Lightweight and auditable models  
✔ Real-world business scenarios  

---

## 📊 Why These Projects Matter

Data inconsistencies between systems can lead to:

- Financial reporting errors  
- Compliance issues  
- Incorrect tax filings  
- Operational confusion  

These projects demonstrate how Excel can be used effectively to detect and resolve such issues using structured logic.

---

## 📸 Screenshots

Each project folder contains its own screenshots explaining:

- Formula implementation  
- Comparison logic  
- Output classification  
- Summary reports  

---

## 🚀 Ideal For

- Finance professionals  
- Accountants  
- Data analysts  
- Excel automation specialists  
- Audit and compliance teams  

---

