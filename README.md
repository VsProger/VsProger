## Baurzhan Saliyev

Software engineer in Astana, Kazakhstan. MSc student at Astana IT University, researching machine learning for atmospheric monitoring. Coding mentor at Tomorrow School, where I design and teach the ML/AI curriculum.

Most of my day-to-day work is backend engineering in Go and Python; my research work is applied ML with an emphasis on explainability and on being honest about what a model cannot do.

---

### Research

**Heavy-metal air pollution forecasting with explainable ML** — ongoing MSc work on 15 years of state monitoring records from Almaty (2006–2020). A reproducible pipeline reconstructs a modelling table from 32 heterogeneous source workbooks, benchmarks 10 tuned regressors, and attributes predictions with SHAP and LIME. Extensions beyond the reference methodology: LSTM/GRU comparison against naive baselines, quantile regression with calibration checks, and a Chow test for structural breaks in the series.

Two of the findings are negative, and the write-up reports them as such: recurrent networks failed to beat a window-mean baseline on this sparsely-sampled, non-stationary series, and the quantile intervals under-cover by 8–12 percentage points.

→ [`almaty-heavy-metals-ml`](https://github.com/VsProger/almaty-heavy-metals-ml)

### Current work

**Intervu** — an adaptive technical-interview platform I am designing: LLM-based extraction of claims from interview transcripts, a Bayesian competence model with time decay, and a strict separation between prediction and decision so that no score is produced during the interview itself. Currently in the design phase — 17 ADRs, an OpenAPI contract, and a PostgreSQL/pgvector schema whose invariants are enforced in the database rather than by convention.

**ML/AI curriculum design** — author of a seven-project production-ML branch plus six electives, taught at Tomorrow School: MLOps serving platform (FastAPI + ONNX Runtime, Prometheus/Grafana, a versioned model registry), recommender systems, LLM engineering with retrieval and agents, document AI, vision tracking, and predictive analytics with SHAP/Fairlearn interpretability. Every project ships a runnable service and a report stating where the system is weak.

---

### Selected projects

| Project | What it is |
|---|---|
| [almaty-heavy-metals-ml](https://github.com/VsProger/almaty-heavy-metals-ml) | ML pipeline for air-quality forecasting: 10-model benchmark, SHAP/LIME, LSTM/GRU, quantile regression, structural-break testing |
| [clipflow](https://github.com/VsProger/clipflow) | Native macOS clipboard manager. Swift 6 with strict concurrency, SwiftUI + AppKit, SwiftData. Fully local |
| [forum](https://github.com/VsProger/forum) | Go web application with sessions, posts, comments and filtering, built on the standard library |
| [Multi-File-Mailer](https://github.com/VsProger/Multi-File-Mailer) | Go API for bulk multipart file delivery and ZIP archiving |
| [tcp-chat](https://github.com/VsProger/tcp-chat) | Concurrent TCP chat server in Go: multiple clients, broadcast and private messaging |

Not public here: an internal Go + React dashboard I wrote and maintain — multi-campus RBAC, backend-enforced time tracking with network allowlisting and heartbeat limits, secure OAuth2 sessions, and an immutable audit log. I also contribute to an Ubuntu fleet-provisioning system for lab machines built on overlayroot and Ansible.

---

### Technologies

**Languages** — Go, Python, Swift, JavaScript, SQL, Bash

**ML / Data** — scikit-learn, XGBoost, CatBoost, TensorFlow/Keras, SHAP, LIME, pandas, NumPy, SciPy

**Backend** — PostgreSQL, SQLite, Redis, chi, REST, GraphQL, TCP/WebSocket, OAuth2

**Other** — Docker, Ansible, React, SwiftUI, Git

---

### Interests

Explainable ML for regulatory and safety-critical use, uncertainty quantification, LLM systems where non-deterministic components are isolated behind reproducible ones, and teaching engineers to build ML systems that survive contact with production.

Reach me at [bbvbatvv@gmail.com](mailto:bbvbatvv@gmail.com).
