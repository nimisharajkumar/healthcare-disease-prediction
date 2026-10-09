# Healthcare Predictive Analytics — Project Report

## Executive summary
This project demonstrates classification on synthetic diabetes-related records. It is an educational example, not a clinical tool.

## Problem statement
Explain how data analysis can explore patterns in clinical measurements, without presenting predictions as diagnoses.

## Dataset
- File: `data/healthcare_diabetes_synthetic.csv`
- Rows: 2,500 synthetic records
- Target: `diabetes_outcome` (1 = simulated positive; 0 = simulated negative)
- Features include age, BMI, glucose, diastolic blood pressure, insulin, pregnancies, family history indicator, and physical activity.
- Missing values are intentionally present to demonstrate preprocessing.

## Methodology
1. Data quality checks and EDA.
2. Stratified train/test split.
3. Median/mode imputation, standardization, and one-hot encoding in a pipeline.
4. Comparison of Logistic Regression, Decision Tree, and Random Forest.
5. Evaluation with accuracy, precision, sensitivity/recall, specificity, F1-score, ROC-AUC, and confusion matrix.
6. Permutation importance.

## Results
Run the notebook and insert the model comparison table and confusion matrix here. Do not report results before running the notebook.

## Ethical considerations
Synthetic data contains no real patient information, but results do not establish clinical validity. Real deployment would require external validation, subgroup analysis, clinical oversight, privacy safeguards, and monitoring.

## Limitations
The data generation process is simplified and cannot capture the complexity of real disease risk. This model must not be used for diagnosis or treatment.
