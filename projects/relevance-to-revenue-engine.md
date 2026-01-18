---
title: Relevance-to-Revenue Engine (Pricing & Explainability)
layout: default
---

[← Back to Projects](/projects)

# Relevance-to-Revenue Engine (Pricing & Explainability)

**An end-to-end decision intelligence system that combines demand modeling, revenue optimization, and learning-to-rank with GenAI explanations, translating complex pricing and relevance decisions into clear, human-understandable insights.**

## Tags & Technologies
<div class="topic-tags">
<span class="topic-tag">Decision Intelligence</span>
<span class="topic-tag">Pricing Analytics</span>
<span class="topic-tag">ML</span>
<span class="topic-tag">NLP</span>
<span class="topic-tag">Explainable AI</span>
<span class="topic-tag">GenAI</span>
<span class="topic-tag">Mistral-7B</span>
<span class="topic-tag">Streamlit</span>
<span class="topic-tag">Production-Ready</span>
</div>

## Key Impact & KPIs

- **Estimated price elasticity quantified** for listings, enabling informed adjustments
- **Expected revenue uplift trade-offs** surfaced in narratives
- **Booking probability insights** contextualized for business decisions
- **Ranking coherence** between demand, quality and revenue signals
- **Stakeholder explainability** via clear plain-English narratives

## Project Overview

### 1. End-to-End Decision Intelligence Pipeline
Designed an end-to-end decision intelligence pipeline that links marketplace demand signals, pricing optimization, and relevance ranking into a single, coherent system—enabling data-backed pricing and prioritization decisions rather than isolated model outputs.

### 2. Demand Sensitivity Quantification
Quantified demand sensitivity through price elasticity modeling, allowing the system to surface how booking likelihood and expected revenue change under different pricing scenarios, supporting informed trade-offs between growth, revenue, and risk.

### 3. Transparent Ranking Framework
Built a transparent ranking framework that balances demand strength, revenue potential, and listing quality, ensuring that top-ranked results are not only relevant but also economically rational.

### 4. GenAI Communication Layer
Introduced a GenAI communication layer (Mistral-7B) that translates numerical model outputs into concise, plain-English explanations—bridging the gap between technical models and non-technical stakeholders without allowing the LLM to influence core decisions.

### 5. Production-Ready System
Delivered a reproducible, demo-ready system with modular pipelines, validation notebooks, and an interactive Streamlit interface—demonstrating how advanced analytics and GenAI can be operationalized responsibly in revenue- and risk-sensitive environments.

## Model Selection Rationale

- **Models/LLMs used:** Regression & ranking models; Flan-T5-Small (templated explanations) + Mistral-7B (rich narratives).
- **Cost & speed:** Flan-T5-Small handled high-volume, low-cost explanation tasks; Mistral-7B used selectively to control inference cost.
- **Fit-for-purpose:** Regression gave interpretable elasticity estimates for pricing decisions; LLMs were a communication layer.

## Links

- [Interactive Demo →](https://huggingface.co/spaces/pranshu-dhingra/Relevance-to-Revenue-Engine)
- [View Code →](https://github.com/pranshu-dhingra/Relevance-to-Revenue-Engine)
