# 📊 Excel Data Appending & Consolidation Project

## 📌 Project Overview

This project demonstrates dynamic data consolidation in Microsoft Excel using formula-based automation.

Multiple city-wise sales sheets were combined into a single structured dataset using the `VSTACK` function. The objective was to create a centralized dataset for analysis and reporting without manual copy-paste.

---

## 📂 Dataset Structure

Each sheet contains identical columns:

- Date  
- SalesRep  
- Product  
- Units  
- Price  
- Total Sales  
- City  
- Region  
- Day  

### City-wise Sheets Included:

- Mumbai_Sales  
- Delhi_Sales  
- Kolkata_Sales  
- Bangalore_Sales  
- Goa_Sales  
- Hyderabad_Sales  

---

## 🔧 Work Performed

### 1️⃣ Identified Common Data Structure
All sheets contained identical column headers and consistent formatting.

---

### 2️⃣ Created Centralized Consolidated Sheet
- Created a new sheet named **Appended_Data**
- Used the `VSTACK` function to dynamically combine data from:
  - Mumbai_Sales
  - Delhi_Sales
  - Kolkata_Sales
  - Bangalore_Sales
  - Goa_Sales
  - Hyderabad_Sales

Example Logic:
- `=VSTACK(Mumbai_Sales!A2:I100, Delhi_Sales!A2:I100, ...)`

---

### 3️⃣ Dynamic Consolidation Approach
- No manual copy-paste used.
- Fully formula-driven solution.
- Automatically updates when new data is added to source sheets.

---

## 🛠 Excel Functions Used

- VSTACK
- Structured References
- Data Alignment Techniques

---

## 🎯 Objective Achieved

✔ Combined multiple city-wise datasets into one master sheet  
✔ Automated data consolidation  
✔ Eliminated manual merging  
✔ Created analysis-ready centralized dataset  

---

## 🚀 Business Value

- Improved reporting efficiency  
- Reduced manual errors  
- Enabled centralized sales analysis  
- Scalable structure for future sheet additions  

---

## 📊 Skills Demonstrated

- Data Consolidation  
- Formula-Based Automation  
- Multi-Sheet Data Handling  
- Structured Dataset Management  
- Dynamic Excel Functions  

---

## 👤 Author

Pritesh Padye
