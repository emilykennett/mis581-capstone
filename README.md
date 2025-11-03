# mis581-capstone
## Small School, Big Impact: Collegiate Athlete Outcomes at Minnehaha Academy (2020-2025)
<br>
This repository contains the full analytical workflow and outputs for Emily Kennett's MIS581 Capstone Project at CSU Global. The project investigates factors predicting advancement from high school to collegiate athletics at a small private school, comparing outcomes to NCAA national benchmarks.

## Structure
```text
mis581-capstone/
├── analysis/
│   ├── Capstone-Analysis-in-R.Rmd                # R-based analysis (data prep, modeling, visualization)
│   ├── Capstone-Analysis-in-Python.ipynb         # Python-based analysis (additional modeling & validation)
│   └── outputs/                                  # Generated analysis outputs
│       ├── figures/                              # Visualizations and plots
│       ├── models/                               # Model summaries and performance metrics
│       └── tables/                               # Cleaned tables and exported data summaries
│
├── data/
│   └── demo/                                     # Anonymized or synthetic sample datasets
│       ├── FOR ANALYSIS - NCAA.csv
│       ├── FOR ANALYSIS - NFHS.csv
│       ├── synthetic_benchmark.csv
│       └── synthetic_predictive.csv
│
├── presentation/
│   └── Small School, Big Impact.pptx             # Final Capstone presentation slides
│
├── .gitignore
└── README.md
```

## Key Components
	•	RQ1: Chi-square test comparing MA vs. NCAA advancement.
	•	RQ2: Predictive modeling (logistic regression, decision tree, random forest, GBM).
	•	Tools: R, Python.

## Privacy Notice
Private datasets are excluded for FERPA compliance and replaced with synthetic equivalents.  
Public reference data (NFHS, NCAA) are included for reproducibility.
