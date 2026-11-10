# Isaque Carvalho

Data Science & AI student at PUC Goiás and intern at a debt-collection company in Goiânia, Brazil. I'm the only technical person there, so I build the models, the pipelines and the API, and I keep the servers running.

Looking for internship and junior roles in data, ML and applied AI.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-2B7A0B?style=flat)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-333333?style=flat&logo=linux&logoColor=white)

## Now

- Building a real-time ops dashboard for the collection floor

## Work projects, rebuilt on synthetic data

Public versions of things I built at work. Every table and number in these repos is invented. No real data.

| Project | What it does | Built with |
|---|---|---|
| [collection-queue-ranker](https://github.com/1isaqu/collection-queue-ranker) | Orders the collection queue by expected recovery. The top 20% of the queue holds 63% of the recovered value, against 51% for the simple rule. Time split that avoids leakage. | LightGBM, MLflow |
| [llm-agent-evals](https://github.com/1isaqu/llm-agent-evals) | A tool-calling analytics agent and the harness that tests it: golden scenarios, eight assertion layers, step and time limits, circuit breaker. CI runs without API keys. | Python stdlib |
| [collections-analytics-api](https://github.com/1isaqu/collections-analytics-api) | Read-only analytics service with 56 routes, cache, connection pool and auth. Tests fail when the OpenAPI contract drifts. | FastAPI, SQL Server |
| [query-verification-gates](https://github.com/1isaqu/query-verification-gates) | Four checks a number from analytical SQL has to pass before it gets reported. Exits non-zero on failure, so it runs in a pipeline. | Python, SQL |
| [call-pace-forecast](https://github.com/1isaqu/call-pace-forecast) | Hourly forecast of call volume, scored with one walk-forward protocol. The simple model stays unless a challenger clearly beats it. | LightGBM, KNN |
| [delinquency-eda-pipeline](https://github.com/1isaqu/delinquency-eda-pipeline) | Staged analysis of overdue receivables: drift, censoring, cleaning and a days-to-pay model. | Pandas |

## Personal projects

<details>
<summary><b>Killswitch Engage</b>: game recommender over 122k titles</summary>
<br>

[Repo](https://github.com/1isaqu/Killswitch-Engage). Random Forest, HDBSCAN, LightFM and cGAN over 122k titles and 10k synthetic users. I found an evaluation error that inflated the results, fixed it and wrote about it on Medium.

</details>

<details>
<summary><b>grindlog</b>: local-first workout tracker</summary>
<br>

[Repo](https://github.com/1isaqu/grindlog). Logs a workout in under 15 seconds, no account and no feed. The interface borrows from Devil May Cry and Resident Evil.

</details>

<details>
<summary><b>gymshark-eda-cleaning</b>: cleaning and EDA on a 44,830-row catalog</summary>
<br>

[Repo](https://github.com/1isaqu/gymshark-eda-cleaning) and [scroll-driven data story](https://1isaqu.github.io/gymshark-eda-cleaning/).

</details>

## Contact

[LinkedIn](https://www.linkedin.com/in/isaque-carvalho-silva-164554282/) · isaquecarvalho2007@gmail.com
