# Nikita Gajbhiye

**Data Science · Machine Learning · Data Engineering**  
Four years of professional experience working with data and ML systems.

[Email](mailto:nikitagajbhiye.ng@gmail.com) · [LinkedIn](https://www.linkedin.com/in/nikita-gajbhiye-101782264)

I build systems across the data lifecycle: ingestion and validation, modeling, evaluation, interpretation, and serving. I am preparing for graduate study in data science, with a focus on **model reliability, distribution shift, and provenance-aware AI systems**.

## Selected systems

### [`taintgate`](https://github.com/Nikita3005/taintgate) — AI-agent tool security

TaintGate evaluates protected tool calls **before execution**. It tracks the origin of agent inputs and combines provenance, security findings, and policy into a deterministic decision.

`untrusted input → provenance → detectors + policy → ALLOW / REVIEW / BLOCK`

- **Implementation:** Python library with integrations for agent frameworks and MCP.
- **Verification:** quickstart examples and a local regression suite with synthetic attack scenarios.
- **Scope:** the suite tests expected behavior for its included scenarios; it is not a general security guarantee.

[Read the documentation and code →](https://github.com/Nikita3005/taintgate)

### [`DriftForge`](https://github.com/Nikita3005/DriftForge) — early warning for model degradation

DriftForge studies whether statistical signals can identify synthetic-data-induced degradation **before aggregate accuracy visibly declines**.

- **Benchmark:** 3 datasets × 3 contamination mechanisms × 5 seeds × 11 levels = **495 controlled conditions**.
- **Evaluation:** detector discrimination, warning lead time, held-out dataset tests, and ablations.
- **Finding:** DriftForge produced positive mean warning lead time in this benchmark, while Jensen–Shannon divergence had stronger conventional degradation discrimination.
- **Limitation:** warning thresholds did not transfer reliably across all datasets.

[Repository →](https://github.com/Nikita3005/DriftForge) · [Technical report →](https://github.com/Nikita3005/DriftForge/blob/main/TECHNICAL_REPORT.md)

## Applied engineering

| Repository | System |
| --- | --- |
| **[Enterprise Customer Intelligence](https://github.com/Nikita3005/enterprise-customer-intelligence-platform)** | Churn prediction, customer lifetime value estimation, and segmentation; SHAP explanations, MLflow tracking, FastAPI inference, tests, and CI. |
| **[Supply Chain Risk Intelligence](https://github.com/Nikita3005/Global-Supply-Chain-Risk-Intelligence-Platform)** | Databricks Bronze–Silver–Gold pipeline for shipment delay prediction, vendor risk analysis, and SQL dashboards. |
| **[HealthLynked Provider Pipeline](https://github.com/Nikita3005/HealthLynked-Provider-Pipeline)** | Hackathon prototype for provider record changes, duplicate detection, confidence scoring, audit trails, and human review. |
| **[Fraud Detection & Risk Modeling](https://github.com/Nikita3005/Fraud-Detection-Risk-Modeling)** | Rare-event classification with attention to precision–recall evaluation and decision thresholds. |
| **[Customer Churn Analytics](https://github.com/Nikita3005/Customer-Churn-Analytics)** | Churn analysis and prediction, with findings presented in a Power BI dashboard. |

## Technical focus

**Data:** Python, SQL, Pandas, NumPy, PySpark, ETL, validation, feature engineering  
**ML:** Scikit-learn, XGBoost, LightGBM, statistical evaluation, SHAP  
**Systems:** FastAPI, MLflow, Docker, testing, model serving  
**Analytics:** Databricks SQL, Power BI, dashboards

I am particularly interested in evaluation methods that reveal failure early and in system boundaries that keep untrusted data from becoming authority.
