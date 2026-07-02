# Logistic Regression Analysis

## Background

Binary logistic regression was performed to identify independent clinical predictors associated with Type 2 Diabetes.

Unlike correlation analysis, logistic regression evaluates the relationship between multiple predictor variables and a binary outcome simultaneously while adjusting for the influence of the other variables.

---

## Objective

To determine which clinical variables independently predict the likelihood of Type 2 Diabetes.

---

## Methods

A binomial logistic regression model was developed in Jamovi.

### Outcome Variable

- Outcome (0 = No Diabetes, 1 = Diabetes)

### Predictor Variables

- Glucose
- BMI
- Age
- Blood Pressure
- Pregnancies

Odds ratios (OR), 95% confidence intervals, and model performance statistics were calculated.

---

## ROC Curve

The ROC curve illustrates the ability of the logistic regression model to distinguish between participants with and without Type 2 Diabetes.

![ROC Curve](../figures/roc_curve.png)

---

## Model Performance

| Metric | Result |
|---------|--------|
| Overall Model Test | χ² = 258, p < .001 |
| McFadden's R² | 0.260 |
| Accuracy | 77.5% |
| Sensitivity | 59.0% |
| Specificity | 87.4% |
| AUC | 0.830 |

The model demonstrated good discrimination between participants with and without Type 2 Diabetes.

---

## Significant Predictors

| Predictor | Odds Ratio | p-value |
|------------|-----------:|---------:|
| Glucose | 1.034 | < .001 |
| BMI | 1.095 | < .001 |
| Blood Pressure | 0.987 | .008 |
| Pregnancies | 1.126 | < .001 |
| Age | 1.017 | .062 |

---

## Interpretation

The logistic regression model identified **glucose concentration**, **body mass index**, **blood pressure**, and **number of pregnancies** as statistically significant predictors of Type 2 Diabetes.

Among these variables, glucose demonstrated the strongest association with diabetes risk.

Age was not statistically significant after adjustment for the remaining predictors.

Overall, the model achieved an AUC of **0.830**, indicating good predictive performance.

---

## Skills Demonstrated

- Binary Logistic Regression
- Odds Ratio Interpretation
- ROC Analysis
- Model Evaluation
- Clinical Data Interpretation
