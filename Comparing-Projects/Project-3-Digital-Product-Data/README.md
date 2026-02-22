# Product Sales Data – New Customer Identification Project

This project focuses on identifying new customers from a Sales dataset by comparing it with an existing customer master list.

The comparison is performed using the XLOOKUP function to determine whether a customer already exists or is a new entry.

---

## 📌 Project Objective

Compare:

- "Sales_Data" sheet  
- "Old_Customer_List" sheet  

And identify:

- Existing Customers  
- New Customers  

---

## 📁 Workbook Structure

### 1️⃣ Sales_Data
Contains transaction-level sales data including customer names.

A new column named **"Exist_Or_Not"** is created in this sheet.

### 2️⃣ Old_Customer_List
Contains the master list of existing customers.

This sheet acts as the reference dataset for comparison.

---

## 🧠 Excel Function Used

- XLOOKUP

---

## 🔎 Logic Implemented

In the "Exist_Or_Not" column inside Sales_Data sheet:

- If Customer Name exists in Old_Customer_List → return Customer Name  
- If Customer Name does not exist → return "New_Customer"

Formula logic used:

XLOOKUP(Customer_Name, Old_Customer_List_Column, Old_Customer_List_Column, "New_Customer")

---

## 📊 Output Interpretation

- If the result shows a Customer Name → It is an existing customer  
- If the result shows "New_Customer" → It is a newly acquired customer  

This makes it easy to filter or highlight new customers for further analysis.

---

## 💼 Business Use Case

This project simulates real business scenarios such as:

- Customer acquisition tracking  
- CRM validation  
- Marketing campaign analysis  
- Sales performance tracking  
- Identifying repeat vs new buyers  

---

## 🚀 Why This Project is Useful

Businesses often need to:

- Identify new customers  
- Measure growth in customer base  
- Track retention vs acquisition  
- Segment customers for targeted marketing  

This Excel model provides a clean and simple way to automate that process using formula logic.

---

## ⚙️ Model Design Approach

✔ Formula-based solution  
✔ No Pivot Tables  
✔ No VBA / Macros  
✔ No Power Query  
✔ Lightweight and easy to audit  

---

## 📸 Screenshots

Refer to the `screenshots` folder to view:

- Sales_Data sheet structure  
- Old_Customer_List sheet  
- XLOOKUP formula implementation  
- Exist_Or_Not column output  
- Highlighted New Customers
---
