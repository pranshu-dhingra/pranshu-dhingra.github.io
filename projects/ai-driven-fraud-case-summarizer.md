---
title: AI-Driven Fraud Case Summarizer (Risk Explainability)
layout: default
---

[← Back to Projects](/projects)

# AI-Driven Fraud Case Summarizer (Risk Explainability)

**An AI-assisted fraud analytics system that combines model risk outputs, SHAP-based explainability, and GenAI narratives to transform raw transaction data and fraud signals into structured, analyst-ready case summaries—supporting faster, more transparent fraud review without automating final decisions.**

## Tags & Technologies
`Fraud Analytics` · `Risk Modeling` · `Explainable AI` · `SHAP` · `NLP` · `GenAI` · `LLMs` · `Prompt Engineering` · `Streamlit` · `BFSI` · `Decision Support`

## Key Impact & KPIs

- **Consolidates risk scores, explainability signals, and narratives** into a single case view
- **Reduces analyst effort** spent interpreting model outputs and raw features
- **Improves transparency** of fraud risk drivers through SHAP-based explanations
- **Standardizes fraud case documentation** with structured summaries
- **Demonstrates responsible human-in-the-loop GenAI** for regulated environments

## Project Overview

### 1. End-to-End Fraud Case Summarization Pipeline
Built an end-to-end fraud case summarization pipeline that ingests transaction-level data, engineered risk features, and model outputs (risk score and probability) and converts them into structured, human-readable fraud case summaries aligned with analyst workflows.

### 2. Model Explainability with SHAP
Integrated model explainability using SHAP by surfacing top contributing risk features, feature–impact pairs, and summarized SHAP reasoning—ensuring analysts can understand why a case was scored as risky, not just the final score.

### 3. Structured Input–Output Schema
Designed a structured input–output schema that separates raw inputs (input_text), predictive signals (risk_score, risk_score_prob), explainability artifacts (top_shap_features, shap_summary), and AI-generated narratives (generated_narrative), enabling clear traceability and audit-friendly case reviews.

### 4. GenAI Narrative Layer
Implemented a GenAI narrative layer that synthesizes SHAP explanations, transaction behavior, and customer context into concise, plain-English fraud summaries—bridging the gap between numerical model outputs and analyst interpretation without influencing core risk scoring.

### 5. Interactive Streamlit Demo
Delivered an interactive Streamlit demo showcasing the full before-and-after workflow—from raw case inputs and explainability signals to AI-generated fraud narratives and recommended actions—demonstrating how predictive models and GenAI can be combined responsibly in fraud operations.

## Links

- [Interactive Demo →](https://pranshu-dhingra.github.io/AI-Driven-Fraud-Case-Summarizer)
- [View Code →](https://github.com/pranshu-dhingra/AI-Driven-Fraud-Case-Summarizer)
