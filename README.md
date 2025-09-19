# 🏙️ Data and Information Quality Project – City of Milan Public Establishments  

This repository contains the work developed for the **Data and Information Quality (DIQ)** course project.  
The goal of the project is to apply a **data preparation pipeline** (and optional data analysis) on a “dirty” real-world dataset provided by the Municipality of Milan.  

---

## 📌 Project Overview  
The project focuses on improving the **data quality** of the dataset:  
- **Dataset:** *Comune di Milano – Pubblici esercizi fuori piano*  
- **Objective:** Detect, clean, and validate the data to ensure consistency and reliability.  
- **Pipeline Steps Implemented:**  
  1. Data Profiling & Data Quality Assessment  
  2. Data Cleaning  
     - Transformation & Standardization  
     - Error Detection & Correction  
     - Handling Missing Values  
     - Deduplication  
  3. [For 3-people groups] Data Analysis Pipeline (before and after cleaning)  

---

## 📂 Dataset Description  
- **Source:** Municipality of Milan open data  
- **Content:** Information about public establishments (*pubblici esercizi*) operating outside the official city plan  
- **Format:** CSV (UTF-8 encoded version provided in repo)  
- **Issues Found:**  
  - Missing values in key attributes  
  - Typos and inconsistent formatting  
  - Duplicates and near-duplicates  
  - Outliers (e.g., incorrect IDs or addresses)  

---

## 🛠️ Methodology  
### Data Preparation Pipeline  
1. **Data Profiling** – Initial exploration, summary statistics, and quality checks.  
2. **Data Cleaning**  
   - **Standardization:** Formatting dates, IDs, and categorical values  
   - **Error Correction:** Fixing typos, resolving inconsistencies  
   - **Missing Data:** Imputation or removal depending on attribute importance  
   - **Deduplication:** Detecting exact/near duplicates based on business rules  


## 📊 Results  
- The cleaning pipeline significantly improved dataset quality (consistency, completeness, uniqueness).  
- Detected and corrected multiple duplicates and inconsistencies.  
- Demonstrated how model performance changes when trained on cleaned vs dirty data.  


