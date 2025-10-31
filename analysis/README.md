# Analysis Directory — MIS581 Capstone Project

This directory contains the R Markdown (`.Rmd`) scripts and related outputs for my **MIS581 Capstone Project**:  
**“Small School, Big Impact: Predictors of Collegiate Athletic Advancement at Minnehaha Academy (2020–2025)”**

---

## 🧠 Project Overview
This analysis investigates predictors of advancement to collegiate athletics among Minnehaha Academy student-athletes.  
It compares institutional advancement rates to national NCAA benchmarks and evaluates how factors such as GPA, multi-sport participation, fine arts involvement, attendance, and financial aid contribute to outcomes.

### Research Questions
**RQ1:** Is there a statistically significant difference between Minnehaha Academy’s advancement rate and the NCAA national average?  
**RQ2:** What student and participation variables best predict advancement to collegiate athletics?

---

## 📂 Directory Structure

```text
analysis/
├── Week6_analysis.Rmd        # Primary R Markdown file (RQ1 & RQ2 analyses)
├── helpers/                  # Utility functions for reproducibility (optional)
├── outputs/
│   ├── figures/              # Saved plots and visualizations (.png)
│   ├── models/               # Model objects and summaries (.txt, .rds)
│   └── tables/               # Exported tables (.csv)
└── README.md                 # This file
```

---

## ⚙️ Reproducibility & Data Handling
- All private datasets (`FOR ANALYSIS - MA Predictive.csv`, `FOR ANALYSIS - MA Benchmark.csv`) are **excluded** for FERPA compliance.
- Public data from NCAA and NFHS are safe for educational redistribution and cited in `data/README.md`.
- Scripts automatically generate **synthetic demo data** to allow reproducible runs without real student data.

---

## 🧩 Key Methods and Models
- **RQ1:** Chi-square goodness-of-fit test  
- **RQ2:** Logistic regression with cross-validation, decision trees, random forests, and gradient-boosted trees  
- Additional analyses include:
  - Variable importance comparisons  
  - Partial dependence plots (PDPs)  
  - Model calibration and ROC curves  
  - Subgroup analysis by gender and financial aid status

---

## 🖥️ Technologies
- **Language:** R (tidyverse, yardstick, rpart, randomForest, gbm, pdp)
- **Environment:** RStudio / R Markdown  
- **Version Control:** Git + GitHub  
- **Visualization:** ggplot2 and custom Minnehaha Academy brand palette

---

## 📊 Outputs
The R Markdown script automatically saves:
- Statistical results in `outputs/tables/`
- Model summaries in `outputs/models/`
- Visualizations (e.g., ROC curves, feature importance) in `outputs/figures/`

---

## 🔒 Privacy Notice
This repository is publicly available for educational demonstration.  
No identifiable student data are included.  
All private or confidential data are excluded via `.gitignore` and replaced by synthetic demo equivalents.
