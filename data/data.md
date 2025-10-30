# 📂 Dataset Information – U.S. Crime Analysis

## Dataset Overview
This project leverages the **"Crime Data from 2020 to Present"** dataset provided by the **Los Angeles Police Department (LAPD)** and hosted on [Data.gov](https://catalog.data.gov/dataset/crime-data-from-2020-to-present).  

The dataset contains detailed crime records across multiple U.S. cities and includes information such as crime type, location, date/time, victim demographics, and other contextual details.

**Note:** The dataset is **not included** in this repository due to its large size. You can download it from the official source using the link above.

---

## Dataset Structure

- **Number of Records:** Over hundreds of thousands of rows (varies by subset)  
- **Columns / Features:** Examples include:
  - `Incident ID` – Unique identifier for each crime report  
  - `Crime Type` – Type of crime (e.g., Burglary, Assault)  
  - `Date/Time` – Date and time when the incident occurred  
  - `Victim Age` – Age of the victim  
  - `Victim Gender` – Gender of the victim  
  - `Victim Race` – Race/ethnicity of the victim  
  - `Location` – Location details (city, state, coordinates)  
  - `Status` – Status of the crime report (e.g., Open, Closed)  
  - `Additional Notes` – Other contextual information, if any  

> ⚠ Some columns may contain missing or incomplete values due to reporting limitations.

---

## Preprocessing & Transformation
To make the dataset suitable for analysis and modeling:  
- Removed or imputed missing values in critical columns  
- Encoded categorical variables for ML algorithms  
- Normalized numeric features where necessary  
- Applied dimensionality reduction (PCA) for computational efficiency  

---

## Notes for Users
- The dataset is publicly available and can be freely accessed from [Data.gov](https://catalog.data.gov/dataset/crime-data-from-2020-to-present)  
- Large dataset size may require downsampling or selective querying for efficient local computation  
- Refer to the notebook for details on preprocessing, EDA, and modeling steps  

---

## Suggested Citation
If you use this dataset for research or projects:  

> Los Angeles Police Department. Crime Data from 2020 to Present. Data.gov. [https://catalog.data.gov/dataset/crime-data-from-2020-to-present](https://catalog.data.gov/dataset/crime-data-from-2020-to-present)
