# Richard Mali

Health data science graduate student at Saint Louis University. Before this I spent years in clinical care and health program management in Malawi, most recently managing an HIV care clinic, where much of my job was making routine clinical data trustworthy enough to act on. I now work on the data and modeling side of that problem.

**Interests:** machine learning for healthcare, reliable AI with incomplete and changing clinical data, AI evaluation, clinical decision support, and infectious disease.

## Selected projects

| Project | What it shows | Stack |
|---|---|---|
| [health-data-warehouse](https://github.com/rmali0/health-data-warehouse) | A tested ETL pipeline that loads CDC chronic disease indicators, openFDA labels and an HTML report into a documented SQLite warehouse. Rebuilding my course version exposed a deduplication key that silently discarded 95% of the source estimates; this version keeps every one and enforces the key in the schema. | Python, pandas, SQLite, pytest, GitHub Actions |
| [diabetes-predictive-modeling](https://github.com/rmali0/diabetes-predictive-modeling) | Leakage-safe classification of diagnosed diabetes from 2024 BRFSS data (test AUC 0.80) and regression of inpatient length of stay, with calibration, precision-recall and a feature ablation. Logistic regression matched the random forest, so I would deploy the simpler model. | R, caret, ranger, glmnet, survey |
| [diabetes-readmission-30day](https://github.com/rmali0/diabetes-readmission-30day) | Epidemiology-style analysis of 30-day readmission in 69,294 adults hospitalized with diabetes: cohort flow, adjusted odds ratios, held-out calibration and a sensitivity analysis. | R, tidyverse, pROC, testthat |

Each repository runs end to end with one command, includes tests and CI, and states what changed from the original course version and why.

## Tools

R (tidyverse, caret, glmnet, survey, R Markdown) · Python (pandas, matplotlib, pytest) · SQL · Git · DHIS2 and electronic medical record systems

## Contact

[LinkedIn](https://linkedin.com/in/richardmali)
