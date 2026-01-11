---
title: Marketing Intelligence Engine (Time-Aware Propensity Modeling)
layout: default
---

[← Back to Projects](/projects)

# Marketing Intelligence Engine (Time-Aware Propensity Modeling)

**An end-to-end, leakage-free machine learning system for predicting term-deposit subscription under real-world campaign dynamics—combining rigorous temporal evaluation, imbalance-aware modeling, and operational metrics to support realistic marketing decisions.**

## Tags & Technologies
`Applied Machine Learning` · `Time-Series Evaluation` · `Campaign Analytics` · `Classification` · `XGBoost` · `Model Validation` · `Imbalanced Learning` · `Explainable ML`

## Key Impact & KPIs

- **Precision improved** from ~14% base rate to ~22% at 50% recall (~1.5× lift)
- **~15% of all subscribers captured** by targeting top 10% scored customers (~1.5× lift)
- **Honest performance reporting** across rolling future periods (ROC-AUC ~0.38–0.63)
- **Leakage-free modeling** ensuring deployable, non-inflated results
- **Actionable thresholding** aligned with campaign capacity and cost trade-offs

## Project Overview

### 1. Leakage-Aware Classification Pipeline
Designed a leakage-aware, end-to-end classification pipeline for term-deposit subscription prediction, starting from deep exploratory analysis through deployment-ready evaluation—explicitly prioritizing realism over optimistic accuracy.

### 2. Post-Outcome Leakage Identification
Identified and removed post-outcome leakage (call duration) through statistical validation and visual analysis, demonstrating how seemingly powerful predictors can invalidate real-world deployment if causal ordering is ignored.

### 3. Temporal and Seasonal Feature Engineering
Engineered temporal and seasonal features (cyclical month encoding) and retained macroeconomic indicators to capture campaign- and economy-driven effects, revealing that subscription behavior is shaped more by context than static customer profiles.

### 4. Rolling Time-Aware Evaluation
Implemented rolling, time-aware train–validation–test evaluation, simulating repeated real-world deployment scenarios and exposing performance variability across campaign regimes rather than relying on a single fragile split.

### 5. Imbalance-Aware XGBoost Classifier
Trained an imbalance-aware XGBoost classifier with regularization and early stopping, selecting the model for its ability to capture non-linear interactions in structured data while remaining interpretable and robust under temporal drift.

### 6. Operational Metrics Evaluation
Evaluated model performance using operational metrics (Precision, Recall@K, Lift) instead of accuracy alone—demonstrating tangible business value under realistic outreach constraints and enabling threshold selection based on capacity and coverage goals.

### 7. Business-Ready Recommendations
Translated model outputs into business-ready recommendations, positioning the system as a decision-support tool for prioritizing outreach, aligning campaign intensity with seasonal engagement, and guiding controlled A/B testing before scaled rollout.

## Links

- [View System →](#)
- [Open Demo →](#)
- [View Code →](#)
