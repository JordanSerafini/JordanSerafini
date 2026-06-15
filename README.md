# Hey, I'm Jordan 👋

AI engineer and full-stack dev based in France. Most of my time goes into NestJS backends, React Native apps and, more and more, ML pipelines. I'm wrapping up a master's level degree (RNCP 7) in AI & Machine Learning at DataScientest x Mines Paris PSL, on top of a Concepteur Développeur d'Applications title (RNCP 6).

Most of my production work (ERP integrations, internal data platform, mobile apps) lives in private repos for clients or my employer, so the public side here is mostly side projects and school work. Happy to walk through the private architecture in a call.

<p>
  <a href="mailto:contact@jordan-s.org"><img src="https://img.shields.io/badge/Email-contact%40jordan--s.org-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://fr.linkedin.com/in/jordan-serafini-63b9b2177"><img src="https://img.shields.io/badge/LinkedIn-Jordan%20Serafini-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

## Some things I've built

**[Compagnon Immo](https://github.com/JordanSerafini/Compagnon_Immo_DataScientest)** - price per m² prediction for French real estate. 5.9M listings, 101 départements, 2019-2026. Random Forest tuned with Optuna and enriched with INSEE socio-economic data, R² 0.958 / RMSE 402€ per m², SHAP for explainability and a Streamlit demo. My DataScientest capstone. I also caught and fixed a data leakage on the way (a feature with VIF 346 that was inflating the score), which is half the lesson.

**[MLOps Météo](https://github.com/JordanSerafini/MlOps_Meteo)** - rain prediction on Australian weather data. The model is deliberately simple, the real subject is the MLOps lifecycle: reproducible training, MLflow tracking and registry, a FastAPI serving layer, DVC for data versioning, the whole thing in Docker Compose.

**Internal data platform** *(private, employer)* - a data-driven analytics layer on top of our EBP ERP. Bronze/silver/gold medallion ETL on PostgreSQL, fed from SQL Server, with several ML models in production: budget overrun prediction (CatBoost/XGBoost/LightGBM stacking, R² ~0.88), billing and project anomaly detection (Isolation Forest), revenue forecasting (Prophet). NestJS for the ETL and API, a decoupled FastAPI service for inference, Next.js dashboards on top.

**EBP App** *(private, client)* - a full ERP suite used daily by field technicians: NestJS 11 API, Next.js back-office, Expo mobile app with offline-first sync on WatermelonDB. The tricky part is a non-destructive bidirectional sync with a closed ERP (EBP, over MSSQL) and a NinjaOne RMM integration.

**SportPoint** *(private)* - a sports coaching and community app. Microservices on NestJS behind an API gateway (auth, coaching, spots, chat, notifications), PostgreSQL/Prisma, and a React Native / Expo app. Where I practice splitting a monolith mindset into services.

**AURA** *(private)* - my personal AI orchestrator: a fleet of agents running on my Linux machine, cron and event driven scheduling, an MCP server exposing them as tools, plus Telegram and voice control. This is where I try out multi-agent patterns before using them anywhere serious.

**[Vélib DPM](https://github.com/JordanSerafini/Velib_DataScientest)** - a data product management case study on the Paris bike-share: personas, KPI framework, 12-month roadmap, MVP design. No ML here, it's the product side of data.

## Stack

TypeScript and Python, mostly.

NestJS, FastAPI, Next.js, React Native / Expo, PostgreSQL, MSSQL, Redis, Docker, plenty of Linux.

ML side: scikit-learn, CatBoost / XGBoost, MLflow, plus the agentic stuff (RAG, pgvector, MCP).

## Contact

contact@jordan-s.org / [LinkedIn](https://fr.linkedin.com/in/jordan-serafini-63b9b2177)
