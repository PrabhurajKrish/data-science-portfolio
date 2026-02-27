# Data Science Portfolio — Prabhuraj Krishnamoorthy

MSc Data Science & AI (Distinction) | Keele University  
Python | SQL | TensorFlow | Databricks | SHAP | Power BI  

---

## Project 1: Predictive Modelling for Diagnostic Pathway Completion

**Context:** NHS-contracted digital health provider, Pan-London service  
**Problem:** Return rates for self-test kits had declined steadily, reaching 65% by 2024. The challenge was identifying which users were genuinely at risk across 1M+ orders.  
**Approach:** Built a Random Forest classifier on Databricks with SHAP analysis to surface key predictors: late-night ordering, deprivation (IMD quintiles 1–3), and sample type. Validated with correlation analysis and A/B testing.  
**Outcome:** Identified a 15–20% high-risk cohort predictable at 79% precision, modelling a 4.5 percentage point return rate uplift. Findings informed intervention design and a major NHS contract bid.  
**Tools:** Python, Databricks, Random Forest, SHAP, Power BI  

📄 [View Report]([Predictors for Non-returns Report .pdf](https://github.com/PrabhurajKrish/data-science-portfolio/blob/main/Predictors%20for%20Non-returns%20Report%20.pdf))

---

## Project 2: Hidden Demand Analysis — Population-Level Forecasting

**Context:** NHS-contracted digital health provider, Pan-London service  
**Problem:** Historical order data was biased by service caps and uneven promotion, making it unreliable for estimating true population demand across underserved areas.  
**Approach:** Engineered 80+ features from ONS Census 2021 and IMD deprivation data across 31K+ LSOAs. Applied K-Means clustering and a TensorFlow ANN with IQR-based outlier filtering and correlation pruning to estimate demand in low-history and capped regions.  
**Outcome:** Improved forecast accuracy by 20%. Findings used as evidence in a Pan-London NHS contract bid to prioritise outreach in underserved communities.  
**Tools:** Python, TensorFlow, K-Means, Databricks, ONS/IMD data, Power BI  

📄 [View Report](./Hidden_Demand_Analysis_SH24.pdf)

---

## Technical Stack

| Area | Tools |
|---|---|
| Languages | Python, SQL, R |
| ML / AI | Random Forest, ANN, LSTM, BERT, XGBoost, SHAP |
| LLMs | RAG Pipelines, Mistral-7B, Prompt Engineering |
| Cloud | Azure, AWS, Databricks, GCP |
| Visualisation | Power BI, Matplotlib, Seaborn, Plotly |
| Governance | NHS Data Standards, Privacy-by-Design, Audit-Ready Documentation |

---

📧 prabhuraj.krishnamoorthy@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/prabhurajkrishnamoorthy)
