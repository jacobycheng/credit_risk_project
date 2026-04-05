# Credit Risk and Default Modeling

## Overview
This project develops models to estimate probability of default (PD) using a consumer credit dataset. The objective is to evaluate predictive performance, calibration, and risk ranking, and extend results to expected loss estimation.

## Dataset
- UCI Default of Credit Card Clients dataset
- ~30,000 observations
- Features include credit limit, repayment history, bill amounts, and payment behavior

## Methods
- Logistic Regression (baseline PD model)
- Random Forest (nonlinear benchmark)
- Evaluation using ROC-AUC, precision-recall, and calibration
- Decile analysis for risk segmentation
- Expected loss estimation using PD × LGD × EAD

## Results
- Repayment history is the strongest predictor of default
- Random forest improves predictive performance, but logistic regression provides better interpretability and calibration
- Models effectively rank borrowers, with higher deciles showing significantly higher default rates

## Key Insights
- Default risk is driven more by repayment behavior than demographics
- Probability calibration is critical for risk-based decision making
- Expected loss provides a more complete measure of risk than PD alone

## Repo Structure
[brief description]

## How to Run
1. Create environment
2. Install dependencies
3. Run notebooks in order