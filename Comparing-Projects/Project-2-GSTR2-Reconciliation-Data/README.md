# GSTR2 Reconciliation Project (Tally vs GST Portal)

This project demonstrates a complete GSTR2 reconciliation process between Tally data and GST Portal data using advanced Excel formulas.

The objective is to identify:

- Missing invoices
- Duplicate entries
- Value mismatches
- Proper reconciliation status

The entire solution is built using Excel formulas without VBA or Power Query.

---

## 📌 Project Objective

Compare:

- "Tally_Data"  
- "GST_Portal_Data"  

And generate a structured reconciliation output that identifies discrepancies between both datasets.

---

## 📁 Workbook Structure

### 1️⃣ Tally_Data
Contains purchase or invoice data exported from Tally.

### 2️⃣ GST_Portal_Data
Contains invoice data downloaded from the GST portal.

### 3️⃣ Reconciliation_Data
This is the core working sheet where:

- Both datasets are combined using VSTACK
- Status checks are performed
- Duplicate detection is applied
- Value mismatch is identified
- Final reconciliation status is generated

### 4️⃣ Summary
Contains Pivot Tables for reconciliation insights.

---

## 🧠 Excel Functions Used

- VSTACK  
- IF  
- COUNTIFS  

---

## 🔎 Reconciliation Logic Explained

### 🔹 Step 1 – Data Combination
Using VSTACK, both Tally_Data and GST_Portal_Data are combined into a single structured dataset.

---

### 🔹 Step 2 – Status Column
Identifies whether a record belongs to:

- Tally  
- GST Portal  

---

### 🔹 Step 3 – Duplicate_Check
Using COUNTIFS:

- If Invoice No appears more than once → Marked as **Duplicate**
- If appears once → Marked as **Unique**

Duplicates are highlighted using Formatting.

---

### 🔹 Step 4 – Value_Mismatch_Detection

Logic applied:

- If invoice exists in both systems AND values match → **Matched**
- If invoice exists in both systems BUT values differ → **Mismatch**
- If not comparable → Empty

---

### 🔹 Step 5 – Reconciliation_Status

Based on business rules:

- Missing in Tally  
- Missing in GST  
- Value_Mismatch  
- Blank (if fully matched)

---

### 🔹 Step 6 – Difference_Check

- Missing_in_GST → Empty  
- Missing_in_Tally → Empty  
- Matched → ₹0.00  
- Value_Mismatch → Displays actual value difference  

This provides clear financial impact visibility.

---

## 📊 Summary Sheet (Pivot Tables)

Two pivot tables are created:

### 1️⃣ Reconciliation_Status | Count of Invoice No
Shows how many invoices fall under:

- Missing in Tally  
- Missing in GST  
- Value_Mismatch  
- Matched  

---

### 2️⃣ Duplicate_Check | Count of Invoice No
Displays:

- Number of Unique invoices  
- Number of Duplicate invoices  

---

## 💼 Business Use Case

This project simulates real-world GST reconciliation used for:

- GSTR2 filing validation  
- Purchase reconciliation  
- Vendor mismatch detection  
- Audit preparation  
- Financial compliance checks  

---

## 🚀 Why This Project is Important

GST reconciliation is critical because:

- Incorrect input credit can cause compliance issues  
- Missing invoices can impact tax claims  
- Value mismatches can create reporting errors  

This model provides a structured and automated Excel-based reconciliation solution.

---

## ⚙️ Model Design Approach

✔ Formula-based reconciliation  
✔ No VBA  
✔ No Power Query  
✔ Fully auditable logic  
✔ Pivot-driven summary reporting  

---

## 📸 Screenshots

Refer to the `screenshots` folder for visual explanation of:

- VSTACK implementation  
- Duplicate detection  
- Value mismatch logic  
- Reconciliation status output  
- Pivot table summary  

