# 🏥 Predicting 30-Day Heart Failure Readmissions

📄 [HF_Readmissions.pdf](./HF_Readmissions.pdf)  
**Author:** Molly Maskrey  
**Date:** June 28, 2025

---

## 🔍 Overview

This paper presents a CMS-aligned, machine learning–driven pipeline to predict 30-day readmissions for heart failure (HF) using multi-year administrative data from the HCUP Nationwide Readmissions Database (2016–2022). It addresses a critical coding shift in ICD-10 definitions that rendered many prior models obsolete.

---

## 🧠 Key Contributions

- **Hybrid Case Identification Logic:**  
  Adjusts for ICD-10 coding migration (I50.x → I11.x/I13.x) to prevent cohort drift across years.

- **Massive Real-World Dataset:**  
  Over 3.6 million HF hospitalizations analyzed using rigorous inclusion/exclusion criteria.

- **SMOTE for Class Imbalance:**  
  Improved sensitivity without contaminating evaluation metrics.

- **Machine Learning Models:**  
  XGBoost + Stacked Ensemble methods evaluated; high-sensitivity operating point selected.

- **Top Predictive Features:**  
  Chronic kidney disease, COPD, ventilator use, cardiac catheterization, anemia.

---

## 📈 Model Performance (XGBoost)

| Metric                  | Value     |
|-------------------------|-----------|
| AUC                     | 0.596     |
| Sensitivity (Recall)    | 99.4%     |
| Specificity             | 3.3%      |
| Positive Predictive Value | 18.9%  |
| Negative Predictive Value | 98.5%  |

---

## 🩺 Clinical Relevance

- **Triaged Risk Stratification:**  
  Proposes a two-tier intervention model: high-sensitivity early flagging + downstream filtering (labs, ED use, polypharmacy).

- **Policy-Ready Design:**  
  Aligns with CMS metrics while accounting for post-2017 ICD logic shifts that distorted prior research.

---

## 📚 Methodology Highlights

- Real-world ICD-10 encoding awareness
- Feature engineering: comorbidities, procedures, demographics
- Decision threshold optimization for intervention prioritization
- SMOTE only applied during training (no data leakage)

---

## 🛠 Future Work

- External validation on other administrative datasets  
- Integration with EHR-based clinical workflows  
- Evaluation of social determinants and lab markers  
- Clinical trial deployment and outcome tracking

---

> "Sensitivity is not just a metric—it is a life-saving imperative."  
> — HF_Readmissions.pdf

---

