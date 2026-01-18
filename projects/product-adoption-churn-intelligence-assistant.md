---
title: Product Adoption & Churn Intelligence Assistant
layout: default
---

[← Back to Projects](/projects)

# Product Adoption & Churn Intelligence Assistant

**An end-to-end agentic decision system that analyzes customer usage signals to surface feature adoption opportunities, actionable enablement playbooks, and explainable churn risk, translating raw telemetry into CSM-ready guidance.**

## Tags & Technologies
<div class="topic-tags">
<span class="topic-tag">Product Analytics</span>
<span class="topic-tag">Agentic AI</span>
<span class="topic-tag">Explainable Systems</span>
<span class="topic-tag">Customer Intelligence</span>
<span class="topic-tag">Python</span>
<span class="topic-tag">Streamlit</span>
<span class="topic-tag">Modular Architecture</span>
</div>

## Key Impact & KPIs

- **Under-utilized feature opportunities surfaced** with clear business rationale
- **Churn risk signals consolidated** into explainable Low / Medium / High classifications
- **Reduced manual analysis** for Customer Success and Product teams
- **Faster, more consistent customer enablement decisions**
- **Trust-first recommendations** through deterministic, auditable logic

## Project Overview

### 1. Agentic Decision Pipeline
Designed an agentic decision pipeline that unifies customer usage telemetry, feature exposure, and behavioral signals into a single assistant—enabling Customer Success teams to move from raw activity data to prioritized, action-ready recommendations.

### 2. Modular Agent Core Architecture
Built a modular Agent Core and tool-based architecture that orchestrates discrete capabilities (usage summarization, feature exposure analysis, recommendation ranking, churn signal detection), ensuring clarity, extensibility, and production-readiness without monolithic logic.

### 3. Explainable Adoption Recommendations
Implemented explainable, rules-driven adoption recommendations that identify high-impact, under-utilized features and generate a concise 1–3 step enablement playbook for the top opportunity—preserving transparency over black-box scoring.

### 4. Interpretable Churn-Risk Framework
Developed an interpretable churn-risk framework that consolidates multiple behavioral indicators (engagement trends, inactivity patterns, support signals) into human-readable Low / Medium / High risk labels with explicit reasoning for each classification.

### 5. Demo-Ready Extensible System
Delivered a demo-ready, extensible system with typed data models, in-repo mock telemetry, memory/context tracking, and dual interfaces (CLI + Streamlit), demonstrating how agentic analytics systems can be operationalized responsibly in customer- and revenue-sensitive environments.

## Model Selection Rationale

- **Models/LLMs used:** Cohort analytics + XGBoost for adoption scoring; Flan-T5-Small to synthesize multi-metric narratives.
- **Actionability & speed:** XGBoost delivered stable, fast scoring for operational pipelines; Flan-T5-Small produced concise insights at low latency.
- **Practicality:** Cohort-first approach preserved temporal context; models focused on interpretable signals product teams can act on.

## Links

- [Interactive Demo →](https://huggingface.co/spaces/pranshu-dhingra/product-adoption-system)
- [View Code →](https://github.com/pranshu-dhingra/product-adoption-system)
