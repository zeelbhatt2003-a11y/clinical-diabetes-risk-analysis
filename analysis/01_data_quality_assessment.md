# Data Quality Assessment

## Background

Before conducting statistical analyses, it is essential to evaluate the quality of the dataset. Data quality assessment helps identify missing values, impossible measurements, and inconsistencies that may affect the validity of statistical analyses.

---

## Objective

To assess the quality of the Pima Indians Diabetes Dataset before performing inferential statistical analyses.

---

## Dataset Overview

- **Dataset:** Pima Indians Diabetes Dataset
- **Sample Size:** 768 participants
- **Software:** Jamovi (Version 2.7)

---

## Data Quality Assessment

Descriptive statistics and frequency distributions were generated to identify potential data quality issues.

Several variables contained values equal to zero that are physiologically implausible in living individuals.

The following variables were identified:

| Variable | Observation |
|----------|-------------|
| Glucose | Contains zero values |
| BloodPressure | Contains zero values |
| SkinThickness | Contains zero values |
| Insulin | Contains zero values |
| BMI | Contains zero values |

These values are commonly interpreted as missing observations within this publicly available dataset and should be considered during future data preprocessing.

Variables including **Pregnancies**, **Age**, **Outcome**, and **DiabetesPedigreeFunction** were retained without modification because zero values are valid for those variables.

---

## Summary

The dataset is suitable for exploratory statistical analysis. However, several physiologically implausible zero values were identified in selected clinical variables. These observations should be addressed during data preprocessing before developing predictive models intended for clinical application.

---

## Skills Demonstrated

- Data quality assessment
- Descriptive statistics
- Identification of missing and implausible values
- Clinical data interpretation
