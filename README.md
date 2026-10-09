# Healthcare Predictive Analytics — Diabetes Outcome Classification

## Overview
A beginner-friendly machine learning project exploring whether simulated health measurements can classify a synthetic record into a positive or negative diabetes outcome group.

## Important data disclosure
**The included dataset is synthetic and generated for demonstration.** It contains no real patient records and does not validate a clinical screening or diagnostic system. Do not use it for medical decisions.

## Objectives
- Inspect data quality and missing values.
- Explore feature distributions and correlations.
- Impute missing values and standardize numeric features within a pipeline.
- Compare Logistic Regression, Decision Tree, and Random Forest.
- Evaluate accuracy, precision, sensitivity/recall, specificity, F1-score, and ROC-AUC.
- Explain predictive signals with permutation importance.
- Discuss privacy, bias, false negatives, false positives, and clinical limitations.

## Repository structure
```text
healthcare-disease-prediction/
├── data/healthcare_diabetes_synthetic.csv
├── results/                 # Add exported metrics/figures here after running
├── reports/                 # Add final report here
├── healthcare_disease_analysis.ipynb
├── requirements.txt
└── README.md
```

## Run locally
1. Install Python 3.10+.
2. Create and activate a virtual environment (recommended).
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open Jupyter and run `healthcare_disease_analysis.ipynb` from top to bottom.

## Metrics
- **Sensitivity/recall:** Proportion of positive records identified.
- **Specificity:** Proportion of negative records identified.
- **Precision:** Proportion of predicted positives that are positive in the dataset.
- **F1-score:** Harmonic mean of precision and recall.
- **ROC-AUC:** Ranking performance across classification thresholds.

## Ethics and limitations
The data is simulated and cannot demonstrate clinical validity. Real-world use would require external validation, subgroup performance checks, clinical oversight, privacy safeguards, and monitoring. False negatives and false positives can both have important consequences. This project is educational and not a diagnostic tool.

## Author
Add your name and internship details here before publishing.
