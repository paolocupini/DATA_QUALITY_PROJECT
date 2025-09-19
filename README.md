# 🏙️ Data and Information Quality Project – City of Milan Public Establishments  

This repository contains the work developed for the **Data and Information Quality (DIQ)** course project.  
The task was to apply a **data preparation pipeline** (and optional data analysis) on a “dirty” real-world dataset provided by the Municipality of Milan.  

---

## 📌 Project Overview  
- **Dataset:** *Comune di Milano – Pubblici esercizi fuori piano*  
- **Objective:** Detect, clean, and validate the dataset to ensure consistency and reliability.  
- **Implementation:** All steps are documented and executed in the Jupyter notebook [`DIQ_project.ipynb`](./DIQ_project.ipynb).  

---

## 📂 Dataset Description  
- **Source:** Municipality of Milan open data  
- **Files Included:**  
  - `Comune-di-Milano-Pubblici-esercizi-fuori-piano.csv`  
  - `Comune-di-Milano-Pubblici-esercizi-fuori-piano-utf8.csv` (UTF-8 encoded version)  
- **Content:** Information about public establishments (*pubblici esercizi*) operating outside the official city plan  
- **Issues Identified:**  
  - Missing values in key attributes  
  - Typos and inconsistent formatting  
  - Duplicate and near-duplicate records  
  - Outliers (e.g., wrong IDs, malformed addresses)  

---

## 🛠️ Methodology  
The complete pipeline is implemented step by step in the notebook:  

1. **Data Profiling & Data Quality Assessment**  
   - Initial exploration of data distribution, missing values, duplicates, and inconsistencies.  

2. **Data Cleaning**  
   - **Transformation & Standardization:** Harmonizing formats (e.g., dates, IDs, text fields).  
   - **Error Detection & Correction:** Fixing typos, normalizing categorical values.  
   - **Missing Data Handling:** Imputation or removal based on attribute importance.  
   - **Deduplication:** Identification and removal of exact/near duplicates.  

3. **[Optional] Data Analysis** *(for 3-people groups)*  
   - Implemented as an extension in the notebook.  
   - Comparison of model performance on **dirty vs cleaned data**.  

4. **Post-Cleaning Quality Check**  
   - Verification that completeness, consistency, and uniqueness improved after cleaning.  

---

## 📊 Results  
- The notebook shows the transition from the raw dataset to a fully cleaned version.  
- Quality metrics demonstrate improved **completeness**, **accuracy**, and **uniqueness**.  
- Additional analysis highlights how models trained on cleaned data outperform those trained on dirty data.  

---

## Authors

Paolo Cupini
Matteo Panarotto
