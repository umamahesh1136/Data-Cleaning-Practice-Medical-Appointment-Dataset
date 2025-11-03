---

## 📌 Practice Project: Data Cleaning & Preprocessing

This project focuses on practicing basic data cleaning and preprocessing steps using Python and Pandas. The dataset used contains medical appointment information, including patient details and their show/no-show status.

---

### ✅ Tasks Done in This Project

* ✅ Loaded the dataset using Pandas
* ✅ Checked missing values using `.isnull().sum()`
* ✅ Detected and removed duplicate rows
* ✅ Fixed incorrect data types

  * Converted **PatientId** & **AppointmentID** from float → int → string
* ✅ Converted date columns to consistent datetime format

  * `ScheduledDay`
  * `AppointmentDay`
* ✅ Standardized text values

  * Trimmed extra spaces
  * Fixed capitalization
  * Converted Gender to `Male` / `Female`
* ✅ Detected invalid age data

  * Removed rows where Age < 0
* ✅ Renamed columns for correct spelling and consistency

  * `Hipertension` → `Hypertension`
  * `No-show` → `No_show`

---

### 📦 Result

The cleaned dataset is:
✔ Free from duplicates
✔ Contains valid Age entries only
✔ Uniform and properly formatted columns
✔ Ready for further analysis or visualization

---

This README summarizes the data cleaning work completed as a **practice exercise** for learning Python data preprocessing.

---
