# SAP vs Warehouse Data Comparison Project

This project demonstrates a real-world reconciliation scenario where Warehouse transactions are compared against SAP records to identify transactions that are not posted in SAP.

The entire comparison model is built using pure Excel formula logic.

---

## 📌 Project Objective

Compare:

- "SAP Data" sheet  
- "Warehouse Data" sheet  

And identify transactions that are missing (not posted) in SAP.

---

## 📁 Workbook Structure

### 1️⃣ SAP Data
Contains transaction records exported from the SAP system.

### 2️⃣ Warehouse Data
Contains warehouse-level transaction records.

XLOOKUP is used in this sheet to check whether each Warehouse Order_ID exists in SAP Data.

### 3️⃣ Missing_Transactions
Displays transactions marked as **"Not_Posted"**, meaning they were not found in SAP.

### 4️⃣ Requirement
Clearly defines the business need:

> Compare SAP and Warehouse Data and identify transactions that are missing in SAP.

---

## 🧠 Excel Function Used

- XLOOKUP

---

## 🔎 Comparison Logic

The core logic implemented:

- If the Order_ID from Warehouse Data exists in SAP Data → return the Order_ID.
- If the Order_ID does not exist in SAP Data → return **"Not_Posted"**.

Formula structure used:

XLOOKUP(Warehouse_Order_ID, SAP_Order_ID_Column, SAP_Order_ID_Column, "Not_Posted")

This ensures:

- Accurate match detection
- Clear identification of missing postings
- No manual filtering required

---

## ⚙️ Model Design Approach

✔ Built without Pivot Tables  
✔ No VBA / Macros used  
✔ No Power Query used  
✔ 100% Formula-Based Reconciliation  

The solution is lightweight, transparent, and easy to audit.

---

## 💼 Business Use Case

This project simulates:

- ERP reconciliation process  
- Warehouse vs SAP transaction validation  
- Posting status verification  
- Month-end reconciliation checks  
- Audit support workflow  

---

## 🚀 Why This Project Matters

In real-world business environments, transactions may exist in operational systems but may not be posted in SAP due to:

- Integration delays  
- Manual posting gaps  
- System synchronization issues  
- Human errors  

This Excel-based reconciliation model provides a clean and structured way to detect such gaps instantly.

---

## 📸 Screenshots

Please refer to the `screenshots` folder to view:

- XLOOKUP formula implementation  
- Order_ID comparison logic  
- "Not_Posted" identification  
- Missing_Transactions output  
- Requirement sheet explanation  

---

