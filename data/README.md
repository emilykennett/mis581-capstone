# Data Directory

This repository does **not** include student-level Minnehaha Academy data (FERPA/PII).

## Local (private) files you must place before knitting
These files are stored locally and are not committed to GitHub:
- `data/FOR ANALYSIS - MA Predictive.csv`  
- `data/FOR ANALYSIS - MA Benchmark.csv`

> ⚠️ These contain individual-level student data and are excluded for privacy and FERPA compliance.

## Reference datasets
The following datasets are **publicly released and safe to include** for noncommercial, educational use:

- **NCAA (2024)** — *Estimated Probability of Competing in College Athletics*  
  Source: NCAA
  URL: [https://ncaaorg.s3.amazonaws.com/research/pro_beyond/2023RES_ProbabilityBeyondHSFiguresMethod.pdf] 
  License: Publicly available summary data, © NCAA. Used here under fair educational use.

- **NFHS (2023)** — *High School Athletics Participation Survey, 2022–23*  
  Source: National Federation of State High School Associations (NFHS).  
  URL: [https://www.nfhs.org](https://www.nfhs.org)  
  License: Publicly available summary data, © NFHS. Used here under fair educational use.

## Synthetic demo
To allow reproducibility without private data, this repository may include small, **synthetic demo files** with the same schema but fabricated values.

Example demo files (fabricated for testing only):
- `data/demo/synthetic_predictive.csv`
- `data/demo/synthetic_benchmark.csv`

These files are auto-generated in R using the script embedded in your R Markdown file.

## Notes
- Private data are automatically ignored by `.gitignore`.
- The analysis scripts are designed to load synthetic or public reference datasets when private files are not available.
