<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1b2a,50:1b4965,100:4FC3F7&height=190&section=header&text=Ibrahima%20Gabar%20Diop&fontSize=44&fontColor=ffffff&animation=fadeIn" alt="header" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=800&color=4FC3F7&center=true&vCenter=true&width=650&lines=Data+Engineer+%40+Rubyx;I+turn+raw+data+into+clean+decisions;Airflow+%7C+dbt+%7C+LightGBM+%7C+FastAPI;Building+for+African+fintech+%F0%9F%8C%8D" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://portfolio-igd.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-4FC3F7?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/ibrahima-gabar-d/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://kaggle.com/ibrahimagabardiop"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle" /></a>
  <a href="mailto:ibrahimagabardiop98@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Open%20to-Opportunities-brightgreen?style=flat-square" alt="Open to opportunities" />
  <img src="https://komarev.com/ghpvc/?username=Gblack98&style=flat-square&color=4FC3F7&label=Profile+Views" alt="Profile views" />
</p>

> **Data Engineer at [Rubyx](https://www.rubyx.io)**, working on lending analytics for financial institutions. On this profile you'll find what I build around one theme I care about: **data & AI for financial inclusion in Africa** 🌍

---

## 🗺️ This profile reads like a data pipeline

Every repo below is a real, working stage of the same story — from raw data to a decision in production:

```mermaid
flowchart LR
    A["📦 Raw data<br/>World Bank API · CSVs<br/>transactions · images"] --> B["🌀 Orchestrate<br/>Apache Airflow"]
    B --> C["🧱 Transform & test<br/>dbt · DuckDB"]
    C --> D["🤖 Model<br/>LightGBM · PyTorch · SHAP"]
    D --> E["⚡ Serve<br/>FastAPI · Docker"]
    E --> F["📱 Product<br/>APIs · Flutter apps"]
```

---

## ⭐ Flagship projects

| Project | The story | Stack |
|---------|-----------|-------|
| ⚡ [**BNPL Risk Engine**](https://github.com/Gblack98/bnpl-risk-engine) | Real-time Buy-Now-Pay-Later risk scoring API — rule knockouts + LightGBM decisioning (**ROC-AUC 0.85**), fully tested & Dockerized | FastAPI · LightGBM · Docker |
| 🌍 [**West Africa Financial Inclusion**](https://github.com/Gblack98/west-africa-financial-inclusion) | Real-data ELT pipeline on financial inclusion across WAEMU countries: World Bank API → dbt → BigQuery → dashboard | Airflow · dbt · BigQuery |
| 🌾 [**GblackAI**](https://github.com/Gblack98/GblackAI-API) | AI crop pest & disease detection with **Wolof voice support**, built for AbiHack 2025 — [live API docs ↗](https://pestai-api.vercel.app/docs) | PyTorch · FastAPI · Flutter |

---

## 🌀 Orchestration — Apache Airflow

*Pipelines that run on schedule, recover from failure, and don't wake anyone up at 3am.*

| Repo | What it demonstrates |
|------|----------------------|
| [airflow-dynamic-dag-factory](https://github.com/Gblack98/airflow-dynamic-dag-factory) | YAML-driven DAG factory — config-as-code pipelines instead of DAG proliferation |
| [airflow-batch-credit-scoring](https://github.com/Gblack98/airflow-batch-credit-scoring) | Daily batch credit scoring: chunked dynamic mapping, versioned models, PSI drift gate |
| [airflow-dbt-cloud-orchestration](https://github.com/Gblack98/airflow-dbt-cloud-orchestration) | Full orchestration of dbt Cloud jobs — manifest parsing, quality gates, intelligent alerting |
| [airflow-cloud-data-platform](https://github.com/Gblack98/airflow-cloud-data-platform) | Production patterns: dynamic task mapping, Kubernetes, custom XCom backend, cost optimization |

---

## 🧱 Analytics Engineering — dbt

*Because a metric nobody trusts is a metric nobody uses.*

| Repo | What it demonstrates |
|------|----------------------|
| [dbt-advanced-patterns](https://github.com/Gblack98/dbt-advanced-patterns) | Incremental models, SCD Type 2, custom macros, slim CI — for fintech data platforms |
| [dbt-testing-and-data-quality](https://github.com/Gblack98/dbt-testing-and-data-quality) | Testing framework with custom macros, automated data-quality monitoring, CI quality gates |
| [credit-scoring-dbt](https://github.com/Gblack98/credit-scoring-dbt) | Raw fintech transactions → ML-ready credit features, engineered in dbt |
| [digital-lending-analytics-dbt](https://github.com/Gblack98/digital-lending-analytics-dbt) | Data warehouse & BI for digital lending — loan portfolio KPIs and cohort analysis |

---

## 🤖 Machine Learning — credit risk & fraud

*Applied to the problems fintech actually has.*

| Repo | What it demonstrates |
|------|----------------------|
| [msme-alternative-credit-scoring](https://github.com/Gblack98/msme-alternative-credit-scoring) | Alternative credit scoring for African MSMEs from mobile-money & behavioral data |
| [aml-graph-neural-network](https://github.com/Gblack98/aml-graph-neural-network) | Anti-money-laundering detection with Graph Neural Networks (GraphSAGE) |
| [fraud-detection-deep-learning](https://github.com/Gblack98/fraud-detection-deep-learning) | Credit-card fraud detection: autoencoder + LightGBM, explained with SHAP |
| [financial-nlp-news-market](https://github.com/Gblack98/financial-nlp-news-market) | Financial news sentiment → market prediction, with FinBERT & LSTM |
| [loan-default-ml-pipeline](https://github.com/Gblack98/loan-default-ml-pipeline) | End-to-end loan-default prediction pipeline with SHAP explainability |

---

## 👤 About me, as a dbt model

```yaml
version: 2

models:
  - name: ibrahima_gabar_diop
    description: "AI & Data Developer — Thiès, Senegal 🇸🇳"
    meta:
      current_role: "Data Engineer @ Rubyx"
      education:
        - "MSc Big Data Analytics · UNCHK (in progress)"
        - "BSc Mathematics & Computer Science"
        - "Sonatel Academy alumnus"
      competitions: [Zindi, Kaggle, GalsenAI, Devpost]
      happy_to_talk_about: [data engineering, LLMs, computer vision]
    columns:
      - name: curiosity
        description: "How things work under the hood"
        tests:
          - not_null
```

## 🛠️ Tech Stack

**Data & Analytics** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=polars&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

**AI / ML** &nbsp;
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-2E7D32?style=flat-square&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=google&logoColor=white)

**Backend & Infra** &nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

**Frontend & Mobile** &nbsp;
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Gblack98&show_icons=true&theme=tokyonight&hide_border=true" height="150" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Gblack98&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="150" alt="Top languages" />
</p>

---

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Cinzel&weight=700&size=22&duration=2000&pause=500&color=4FC3F7&center=true&vCenter=true&width=750&height=80&lines=One+pipeline+to+rule+them+all" alt="footer quote" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4FC3F7,50:1b4965,100:0d1b2a&height=100&section=footer" alt="footer" />
</p>
