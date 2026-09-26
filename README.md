# Nikita Gajbhiye

**Data Science · Machine Learning · Data Engineering**

I build data and ML systems with an interest in what makes them dependable: clean inputs, meaningful evaluation, interpretable results, and safe behavior when conditions change.

[![Email](https://img.shields.io/badge/Email-Get%20in%20touch-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:nikitagajbhiye.ng@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nikita-gajbhiye-101782264)

---

## What I work on

| 🔐 Trust | 📉 Reliability | 🏗️ Data to decisions |
| --- | --- | --- |
| How should AI agents handle untrusted information? | Can we detect model degradation early? | How do we turn raw data into useful models and insights? |

## Selected work

### 01 / Protecting AI-agent actions

#### 🛡️ [TaintGate](https://github.com/Nikita3005/taintgate)

> **The question:** What happens when instructions hidden in a webpage, document, or tool result reach an agent that can take action?

TaintGate is a Python runtime guard for protected tool calls. It tracks where inputs came from, checks security-relevant findings, and applies deterministic policy **before a tool executes**.

`Untrusted input` → `Provenance` → `Policy` → **ALLOW · REVIEW · BLOCK**

The repository includes a local attack regression suite and integrations for agent frameworks and MCP. The suite checks expected decisions on its included scenarios; it does not claim complete protection against every attack.

**Explore:** [Code, quickstart, and attack suite →](https://github.com/Nikita3005/taintgate)

---

### 02 / Detecting model failure earlier

#### 📉 [DriftForge](https://github.com/Nikita3005/DriftForge)

> **The question:** Can statistical signals warn us about model degradation before an aggregate performance metric visibly falls?

DriftForge benchmarks early warnings for synthetic-data-induced model degradation across **495 controlled conditions**. It compares drift detectors, measures warning lead time, and tests how well thresholds transfer between datasets.

`Changing data` → `Drift signals` → `First warning` → `Observed accuracy drop`

The project reports its limitations alongside its results, including unstable threshold transfer. That makes it a study of *when a warning is useful*, as well as whether a detector can distinguish degraded conditions.

**Explore:** [Benchmark, results, and technical report →](https://github.com/Nikita3005/DriftForge)

---

### 03 / Building systems around data

| Project | From → to | What you’ll find |
| --- | --- | --- |
| **[Enterprise Customer Intelligence Platform](https://github.com/Nikita3005/enterprise-customer-intelligence-platform)** | Customer data → features → models → explanations → API | Churn prediction, customer lifetime value, segmentation, SHAP, MLflow, FastAPI, automated tests, and CI. |
| **[Supply Chain Risk Intelligence Platform](https://github.com/Nikita3005/Global-Supply-Chain-Risk-Intelligence-Platform)** | Shipment data → Bronze → Silver → Gold → risk insights | A Databricks pipeline for delay prediction, vendor risk analysis, experiment tracking, and SQL dashboards. |

### 04 / Applying analytics to specific decisions

| Project | Decision it supports |
| --- | --- |
| **[HealthLynked Provider Pipeline](https://github.com/Nikita3005/HealthLynked-Provider-Pipeline)** | Which provider records can be updated confidently, and which need human review? A hackathon prototype with change detection, duplicate matching, confidence scoring, and audit trails. |
| **[Fraud Detection & Risk Modeling](https://github.com/Nikita3005/Fraud-Detection-Risk-Modeling)** | How should rare fraudulent transactions be identified while balancing missed fraud against investigation costs? |
| **[Customer Churn Analytics](https://github.com/Nikita3005/Customer-Churn-Analytics)** | Which customer patterns are associated with churn, and how can those findings be communicated through a Power BI dashboard? |

## Technical toolkit

**Data:** Python · SQL · Pandas · NumPy · PySpark · ETL · Data validation  
**Machine learning:** Scikit-learn · XGBoost · LightGBM · Feature engineering · Model evaluation  
**Systems:** FastAPI · MLflow · Docker · Testing · Model serving  
**Interpretation and analytics:** SHAP · Power BI · Databricks SQL · Dashboards

## What I’m exploring now

I’m particularly interested in **early warnings for model degradation**, **reproducible evaluation**, and **provenance-aware security for AI agents**.

---

**Let’s connect:** [Email](mailto:nikitagajbhiye.ng@gmail.com) · [LinkedIn](https://www.linkedin.com/in/nikita-gajbhiye-101782264)
