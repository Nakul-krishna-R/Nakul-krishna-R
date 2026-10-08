<div align="center">

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&pause=1000&color=1A56DB&center=true&vCenter=true&width=500&lines=Hi%2C+I'm+Nakul+Krishna+R;Data+Scientist+%7C+ML+Engineer;MSc+%40+UCD+Dublin;Building+things+that+work" alt="Typing SVG" /></a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nakul-krishna-r/)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nakulkrishna96@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nakul-krishna-R)

</div>

---

### What I do

MSc Data and Computational Science graduate (UCD). I build supervised learning pipelines end to end: feature engineering, gradient boosting with automated hyperparameter search, out-of-time validation to catch leakage, and FastAPI model serving. Physics background — I default to reasoning from first principles before reaching for a library.

Currently open to Data Scientist and ML Engineer roles in Dublin. Full work rights on Stamp 1G.

---

### Featured Project

**[Fintech Risk Intelligence — SEC 8-K Filing Classifier](https://github.com/Nakul-krishna-R/fintech-risk-intelligence)**

End-to-end ML pipeline on 2,553 SEC 8-K filings. Local LLM (Phi-3 Mini via Ollama) extracts structured risk signals from raw disclosure text. Chunks embedded with `all-mpnet-base-v2` into ChromaDB. RAG used as a feature engineering layer, not a chatbot. LightGBM + Optuna classifies whether a stock will underperform SPY over 5 trading days. Strictly out-of-time evaluation: trained 2021–2023, tested 2024.

| Stat | Value |
|---|---|
| Filings ingested | 2,553 |
| Text chunks | 4,910 |
| Embedding dims | 768 |
| Optuna trials | 50 |
| AUROC (2024 holdout) | **0.52** |

> AUROC 0.52 is the honest number. Coarse LLM-extracted features from 8-K filings do not carry enough alpha to beat random on a market-relative task. The pipeline, methodology, and infrastructure are the point.

`Python` `LightGBM` `Optuna` `sentence-transformers` `ChromaDB` `FastAPI` `Ollama`

---

### Projects

| Project | What it does | Stack | Key result |
|---|---|---|---|
| [Fraud Detection Pipeline](https://github.com/ACM40960/Fraud-Detection-in-Financial-Transactions) | End-to-end supervised learning on 594K transactions, 39 engineered features, OOT evaluation, FastAPI serving | LightGBM, XGBoost, Optuna, FastAPI | AUROC 0.9993 · AUPRC 0.9578 · <10ms latency |
| [Dublin Rental Market Analysis](https://github.com/Nakul-krishna-R/dublin-rental-analysis) | Scraped ~500 live Daft.ie listings, joined against 18 years of CSO RTB data to quantify the newcomer rent gap | Playwright, SQL, Power BI | 21% average premium over official rates |
| [Pricing Anomaly Detection](https://github.com/Nakul-krishna-R/Zepto_SQL) | SQL-only reconciliation of a SKU-level dataset — currency mismatches, zero-value entries, discount outliers | PostgreSQL, Window Functions | Isolated revenue leakage exposure for corrective action |
| [Customer Segmentation](https://github.com/Nakul-krishna-R/Customer_behavior_analysis) | Clustered 3,900 transactions into behavioural cohorts, surfaced high-value upsell segment | Python, SQL, Power BI | 839-customer retention cohort identified |

---

### Skills

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

**Machine Learning**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-2196F3?style=flat-square&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-4B0082?style=flat-square&logoColor=white)

**LLM / Embeddings**

![sentence-transformers](https://img.shields.io/badge/sentence--transformers-4B0082?style=flat-square&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-1A1A2E?style=flat-square&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)

**Serving and Tooling**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

---

### GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=Nakul-krishna-R&show_icons=true&theme=default&hide_border=true&count_private=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nakul-krishna-R&layout=compact&theme=default&hide_border=true" />

</div>

---

### Education

**MSc Data and Computational Science** — University College Dublin, 2024–2025  
Statistical Machine Learning · Regression Analysis · Bayesian Analysis · Multivariate Analysis

**BSc Physics, First Class Honours** — Mahatma Gandhi University, 2020–2023  
Calculus · Linear Algebra · Probability · Differential Equations

---

<div align="center">
<sub>Open to work · Dublin · Stamp 1G · nakulkrishna96@gmail.com</sub>
</div>
