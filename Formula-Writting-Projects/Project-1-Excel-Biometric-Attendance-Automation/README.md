
# 📊 Biometric Attendance Data Processing & Automation (Excel)

## 📌 Project Overview

This project focuses on cleaning, structuring, and automating raw biometric attendance data using Microsoft Excel formulas.

The objective was to transform unstructured biometric logs into a structured and analysis-ready attendance report with automated classification.

---

## 🎯 Project Objectives

- Separate raw combined biometric data into structured columns
- Standardize employee full names
- Extract designation and department details
- Automate attendance classification (Half-Day / Full-Day)
- Improve data accuracy and reporting efficiency

---

## 🔧 Work Performed

### 1️⃣ Raw Data Cleaning & Separation
- Processed unstructured biometric log data.
- Used `TEXTSPLIT` formula to separate combined text values into structured columns.
- Converted raw entries into clean tabular format.

---

### 2️⃣ Full Name Standardization
- Created a new **Full_Name** column.
- Used `TEXTJOIN` to combine:
  - Title (Mr./Ms.)
  - First_Name
  - Last_Name
- Applied proper spacing and handled blank values.
- Ensured consistent and professional naming format.

---

### 3️⃣ Designation & Department Structuring
- Extracted and structured **Designation** and **Department** fields using appropriate formulas.
- Cleaned inconsistent values.
- Prepared data for filtering and departmental reporting.

---

### 4️⃣ Attendance Classification Logic
- Created an automated **Half_Day / Full_Day** column.
- Calculated working hours using `In_Time` and `Out_Time`.
- Applied logical conditions using `IF` formula:
  - Full Day → If working hours met defined threshold
  - Half Day → If working hours were below required limit
- Ensured accurate and automated attendance status generation.

---

## 🛠 Excel Functions Used

- TEXTSPLIT
- TEXTJOIN
- IF
- Time Difference Calculation
- Logical Conditions
- Data Cleaning Techniques

---

## 📊 Outcome

- Transformed raw biometric logs into structured attendance dataset
- Automated employee name formatting
- Automated attendance classification
- Reduced manual effort
- Improved reporting clarity and accuracy

---

## 🚀 Skills Demonstrated

- Excel Data Cleaning
- Data Transformation
- Automation using Formulas
- Logical Problem Solving
- Attendance Reporting Structure

---

## 👤 Author

Pritesh Padye
