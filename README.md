<div align="center">

# 👋 Hey, I'm Isaque
</div>

Data Science & AI student at PUC Goiás (4th semester) and the **only technical hire** at a debt-collection company in Goiânia, Brazil. That means I own the whole stack there: models, pipelines, and the servers they run on. A lot of what I actually know came from keeping production systems alive, not from a classroom.

---

## 🧭 Right Now

- 💼 Running data & infra solo for a debt-collection company, no backup, no handoff, just uptime
- 📊 Building an internal real-time ops dashboard from scratch, accessibility contrast math included
- 🏆 Competing in **Jump Start 2026** (SAE Brasil × Toyota), building around a BPM-driven solution
- 🎓 4th semester of Data Science & Artificial Intelligence @ PUC Goiás

---

## ⚙️ Stack

**Core**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Data & ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**Backend & Infra**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 🛠️ A Few Things I've Built

### 🏢 From the job, rebuilt on synthetic data

Public versions of problems I solve at work in debt collections. Every table, portfolio and number in these repos is invented, and none of them touch real data.

### 🤖 [llm-agent-evals](https://github.com/1isaqu/llm-agent-evals)
A tool-calling analytics agent plus the harness that checks it: golden scenarios, eight assertion layers, a reliability ledger and run guards (step and time ceilings, call-spiral detection, circuit breaker). A deterministic mock model keeps CI free of API keys, and the runtime uses only the standard library.

### ⏱️ [call-pace-forecast](https://github.com/1isaqu/call-pace-forecast)
"Is the operation on pace?", answered hour by hour. A lookup baseline, KNN and LightGBM quantile bands, all scored with the same walk-forward protocol. A challenger only replaces the baseline if it clearly beats it, and when it doesn't, the simple model stays.

### 🔒 [query-verification-gates](https://github.com/1isaqu/query-verification-gates)
Four gates a number from analytical SQL has to pass before anyone reports it: the columns exist, two independent routes reconcile, every filter is declared, every code-to-label mapping is re-derived. It exits non-zero on failure, so it fits in a pipeline.

### 🔌 [collections-analytics-api](https://github.com/1isaqu/collections-analytics-api)
A read-only FastAPI service over SQL Server: 56 routes, one response envelope, cache, connection pool and auth. The OpenAPI document is generated from the app, and tests fail when the contract drifts.

Also: [collection-queue-ranker](https://github.com/1isaqu/collection-queue-ranker) (LightGBM work-queue ranker with MLflow and a leakage-safe time split) and [delinquency-eda-pipeline](https://github.com/1isaqu/delinquency-eda-pipeline) (staged analysis of overdue receivables: drift, censoring, cleaning, days-to-pay model).

### 🎮 On my own time

#### 📕 [Killswitch Engage](https://github.com/1isaqu/Killswitch-Engage)
A recommendation engine for game libraries too big to make sense of by hand, built out of a very real backlog problem. A 4-layer ML pipeline (Random Forest, HDBSCAN, LightFM, cGAN) over 122k titles and 10k synthetic users, with a write-up on Medium.

#### 💪 [grindlog](https://github.com/1isaqu/grindlog)
A mobile-first workout tracker with a gothic/cybersigilism interface (Devil May Cry and Resident Evil as UI references), because a gym log doesn't have to look like a spreadsheet.

#### 🧹 [gymshark-eda-cleaning](https://github.com/1isaqu/gymshark-eda-cleaning)
End-to-end exploratory analysis and cleaning on a 44,830-row retail catalog, with a [scroll-driven data story](https://1isaqu.github.io/gymshark-eda-cleaning/): the unglamorous groundwork most tutorials skip straight past.

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=1isaqu&show_icons=true&theme=dracula&include_all_commits=true&count_private=true" alt="GitHub Stats" height="180em"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=1isaqu&layout=compact&langs_count=7&theme=dracula" alt="Top Langs" height="180em"/>

<a href="https://git.io/streak-stats">
  <img src="https://streak-stats.demolab.com?user=1isaqu&theme=dracula" alt="GitHub Streak" />
</a>

</div>

---

## 📫 How to Reach Me

<div align="center">
  <a href="https://www.linkedin.com/in/isaque-carvalho-silva-164554282/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://www.instagram.com/1isaqu?igsh=ZWhjbWZ2N3lzZWo3">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/>
  </a>
  <a href="https://discord.com/users/320643197393043486">
    <img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"/>
  </a>
</div>
