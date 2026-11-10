# Isaque Carvalho

Data Science & AI student at PUC Goiás and intern at a debt-collection company in Goiânia, Brazil. I'm the only technical person there, so I build the models, the pipelines and the API, and I keep the servers running.

Looking for internship and junior roles in data, ML and applied AI.

## Work projects, rebuilt on synthetic data

Public versions of things I built at work. Every table and number in these repos is invented. No real data.

- **[collection-queue-ranker](https://github.com/1isaqu/collection-queue-ranker)**: LightGBM model that orders the collection queue by expected recovery. The top 20% of the queue holds 63% of the recovered value, against 51% for the simple rule. MLflow tracking and a time split that avoids leakage.
- **[llm-agent-evals](https://github.com/1isaqu/llm-agent-evals)**: a tool-calling analytics agent and the harness that tests it. Golden scenarios, eight assertion layers, step and time limits, circuit breaker. A deterministic mock model lets CI run without API keys.
- **[collections-analytics-api](https://github.com/1isaqu/collections-analytics-api)**: read-only FastAPI service over SQL Server. 56 routes, cache, connection pool, auth. Tests fail when the OpenAPI contract drifts.
- **[query-verification-gates](https://github.com/1isaqu/query-verification-gates)**: four checks a number from analytical SQL has to pass before it gets reported. Exits non-zero on failure, so it runs in a pipeline.
- **[call-pace-forecast](https://github.com/1isaqu/call-pace-forecast)**: hourly forecast of call volume. Lookup baseline, KNN and LightGBM quantile bands, all scored with the same walk-forward protocol. The simple model stays unless a challenger clearly beats it.
- **[delinquency-eda-pipeline](https://github.com/1isaqu/delinquency-eda-pipeline)**: staged analysis of overdue receivables: drift, censoring, cleaning and a days-to-pay model.

## Personal projects

- **[Killswitch Engage](https://github.com/1isaqu/Killswitch-Engage)**: game recommender over 122k titles and 10k synthetic users (Random Forest, HDBSCAN, LightFM, cGAN). I found an evaluation error that inflated the results, fixed it and wrote about it on Medium.
- **[grindlog](https://github.com/1isaqu/grindlog)**: local-first workout tracker. The interface borrows from Devil May Cry and Resident Evil.
- **[gymshark-eda-cleaning](https://github.com/1isaqu/gymshark-eda-cleaning)**: cleaning and EDA on a 44,830-row product catalog, with a [scroll-driven data story](https://1isaqu.github.io/gymshark-eda-cleaning/).

## Stack

Python, SQL (T-SQL, PostgreSQL), Pandas, scikit-learn, LightGBM, XGBoost, PyTorch, FastAPI, React, Docker, MLflow, Langfuse, Linux.

## Contact

[LinkedIn](https://www.linkedin.com/in/isaque-carvalho-silva-164554282/) · isaquecarvalho2007@gmail.com
