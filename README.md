<div align="center">

# Nikita Gajbhiye

**Data Science · Machine Learning · Data Engineering**

Four years of professional experience working with data and machine learning

[Email](mailto:nikitagajbhiye.ng@gmail.com) · [LinkedIn](https://www.linkedin.com/in/nikita-gajbhiye-101782264)

</div>

---

## 01 / Research statement

I work on data and machine learning systems with an emphasis on **reliability, interpretability, and evaluation**. My projects span data preparation, predictive modeling, experiment tracking, and the behavior of systems after a model is trained.

I am preparing for graduate study in data science. Two questions currently guide my independent work: **Can we recognize model degradation early enough to act?** And **how can AI agents use untrusted information without allowing it to direct their actions?**

## 02 / Selected research and systems

<table>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/Nikita3005/taintgate">TaintGate</a></h3>
<p><em>Provenance-aware security for AI agents</em></p>

<p><strong>Problem.</strong> An agent may encounter instructions in untrusted content before making a consequential tool call.</p>

<p><strong>Approach.</strong> Track input provenance and evaluate protected tool calls with detectors and deterministic policy: <code>ALLOW</code>, <code>REVIEW</code>, or <code>BLOCK</code>.</p>

<p><strong>Artifact.</strong> Python library, framework and MCP integrations, quickstart examples, and a local regression suite using synthetic attack scenarios.</p>

<p><a href="https://github.com/Nikita3005/taintgate">Code and documentation →</a></p>

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/Nikita3005/DriftForge">DriftForge</a></h3>
<p><em>Early warning for model degradation</em></p>

<p><strong>Question.</strong> Can statistical signals warn of synthetic-data-induced degradation before aggregate model accuracy substantially falls?</p>

<p><strong>Approach.</strong> Compare drift detectors across <strong>495 controlled conditions</strong>, measuring both degradation discrimination and warning lead time.</p>

<p><strong>Finding.</strong> The evaluated methods show a trade-off between conventional discrimination and warning timing. Threshold transfer across datasets remains unstable.</p>

<p><a href="https://github.com/Nikita3005/DriftForge">Code and results →</a> · <a href="https://github.com/Nikita3005/DriftForge/blob/main/TECHNICAL_REPORT.md">Technical report →</a></p>

</td>
</tr>
</table>

### Benchmark excerpt: DriftForge

| Detector | ROC-AUC | Mean warning lead time |
| --- | ---: | ---: |
| Jensen–Shannon divergence | 0.907 | −0.089 |
| Wasserstein distance | 0.891 | −0.092 |
| DriftForge | 0.831 | +0.319 |

Positive lead time indicates that the first warning preceded the project-defined accuracy-drop point. These are results from a **controlled benchmark**, not a claim of general performance on real-world deployment data. See the [methodology and limitations](https://github.com/Nikita3005/DriftForge/blob/main/TECHNICAL_REPORT.md).

## 03 / Applied ML and data engineering

| Project | System and contribution |
| --- | --- |
| **[Enterprise Customer Intelligence](https://github.com/Nikita3005/enterprise-customer-intelligence-platform)** | Modular workflows for churn prediction, customer lifetime value estimation, and segmentation, with SHAP explanations, MLflow tracking, FastAPI inference, automated tests, and CI. |
| **[Supply Chain Risk Intelligence](https://github.com/Nikita3005/Global-Supply-Chain-Risk-Intelligence-Platform)** | A Databricks Bronze–Silver–Gold pipeline supporting shipment delay prediction, vendor risk analysis, and SQL dashboards. |
| **[HealthLynked Provider Pipeline](https://github.com/Nikita3005/HealthLynked-Provider-Pipeline)** | Hackathon prototype for provider record change and duplicate detection, confidence scoring, audit trails, and human review. |
| **[Fraud Detection & Risk Modeling](https://github.com/Nikita3005/Fraud-Detection-Risk-Modeling)** | Classification of highly imbalanced transaction data, emphasizing precision–recall evaluation and decision thresholds. |
| **[Customer Churn Analytics](https://github.com/Nikita3005/Customer-Churn-Analytics)** | Customer behavior analysis and churn modeling, with findings communicated through a Power BI dashboard. |

## 04 / Research interests

- Distribution shift and early-warning model monitoring
- Reproducible evaluation and data-centric machine learning
- Model interpretation and decision-relevant metrics
- Data provenance and security boundaries in AI-agent systems

## 05 / Technical foundation

**Programming and data:** Python · SQL · Pandas · NumPy · PySpark · ETL · Data validation  
**Modeling and evaluation:** Scikit-learn · XGBoost · LightGBM · Feature engineering · SHAP  
**Systems and analytics:** FastAPI · MLflow · Docker · Databricks SQL · Power BI

---

<div align="center">

[Email](mailto:nikitagajbhiye.ng@gmail.com) · [LinkedIn](https://www.linkedin.com/in/nikita-gajbhiye-101782264) · [GitHub](https://github.com/Nikita3005)

</div>
