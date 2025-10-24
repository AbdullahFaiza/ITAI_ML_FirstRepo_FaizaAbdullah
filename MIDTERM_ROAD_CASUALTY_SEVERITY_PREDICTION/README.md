# Road Casualty Severity Prediction: Data Preprocessing & Feature Engineering  
**FLAM – Fusion Learning & AI Minds**
---

## **Project Overview**  
This repository contains the **mid-term project** for a Machine Learning course, focused on **data preprocessing and feature engineering** using the **UK Road Casualty Statistics (2022)** dataset.  
Our goal was to transform raw, real-world data (61,352 rows × 20 columns) into an **ML-ready format** to predict **casualty severity** (1: fatal, 2: serious, 3: slight) using supervised learning.  

We followed **Lab 6 guidelines** and implemented end-to-end preprocessing techniques, including:  
- Missing value imputation  
- Categorical encoding  
- Outlier handling  
- Feature engineering  
- Scaling/normalization  
- Reproducible pipeline  

**Final Output:** A clean, engineered dataset ready for modeling with potential **75–85% accuracy** in severity prediction.

---

## **Dataset**  
- **Source:** [Kaggle – Road Accidents Data 2022](https://www.kaggle.com/datasets/juhibhojani/road-accidents-data-2022)  
- **File:** `dft-road-casualty-statistics-casualty-provisional-mid-year-unvalidated-2022 (1).csv`  
- **Rows:** 61,352  
- **Columns:** 20  
- **Target:** `casualty_severity` (1 = fatal, 2 = serious, 3 = slight)  
- **Key Features:** age, sex, pedestrian status, IMD decile, LSOA, vehicle type  

> **Note:** The dataset uses `-1` as a placeholder for missing values.

---

## **Project Structure**  

MIDTERM_ROAD_CASUALTY_SEVERITY_PREDICTION/
├── FLAM_MIDTERM_NOTEBOOK.ipynb          # Main Jupyter notebook with all steps

├── FLAM_MIDTERM_NOTEBOOK.pdf            # PDF export of notebook

├── FLAM-MIDTERM DETAILED PROPOSAL.pdf   # Detailed project report
-├── Midterm_FLAM_Proposal-1.pdf          # Initial proposal
-├── data/                                # Folder for dataset (add CSV here)
-├── cleaned_road_casualty_flame.csv      # Output cleaned dataset (generated)
-├── requirements.txt                     # Dependencies
-└── README.md                            # This file


## **Team Members**  
- **Faiza Abdullah**  
- **Lufei Yu**  
- **Michael Joseph**  
- **Muhammadayan Syed**  
