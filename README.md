# Anesu Ruzvidzo

I build AI-native tools and full-stack applications — retrieval systems, observability platforms, and production-grade products shipped end to end. Currently finishing a CS degree at Cleveland State (May 2026), based in Chicago on F-1/OPT, and open to Applied AI Engineer and Full-Stack Engineer roles in Canada. Eligible for Canada's Global Talent Stream.

Four projects in production. Every one built from scratch: backend, database, frontend, and deployment.

## Stack

`TypeScript` `Python` `Next.js` `React` `Node.js` `FastAPI` `Flask`
`PostgreSQL` `pgvector` `Redis` `Supabase` `Drizzle ORM` `asyncpg` `Docker` `AWS`
`Anthropic Claude API` `Agentic Systems` `RAG` `Hybrid Search` `Sentence Transformers`
`LLM Observability` `Tool Use` `Prompt Engineering`
`Elasticsearch` `Pandas` `Scikit-learn` `PySpark` `Tableau`

## Projects

**BasinIQ — Alberta Energy RAG System**
[GitHub](https://github.com/anesuruzvidzo1/basiniq) · [Live demo](https://basiniq.vercel.app)

Natural language queries over AER regulatory directives and Alberta well license data. Hybrid retrieval combining Elasticsearch BM25 and pgvector dense search, merged with Reciprocal Rank Fusion and reranked by a cross-encoder. Claude tool use loop with two tools: a SQL query tool over well data and a document search tool over indexed directive chunks. Multi-turn sessions persisted in PostgreSQL JSONB. Next.js 16 frontend with grouped source citations and session history.

**Argus — LLM Observability Platform**
[GitHub](https://github.com/anesuruzvidzo1/argus) · [Live demo](https://argus-dashboard-phi.vercel.app)

Most observability tools don't understand tokens, tool calls, or session cost rollup. Argus does. Wraps the Anthropic SDK with zero application code changes. Every call is captured and streamed to a real-time dashboard. FastAPI, asyncpg, PostgreSQL for trace storage, Redis pub/sub for fan-out, SSE-powered Next.js 15 dashboard. Production-deployed on Railway and Vercel.

**Lumin — AI Data Analysis Platform**
[GitHub](https://github.com/anesuruzvidzo1/lumin) · [Live demo](https://lumin-tau.vercel.app)

Analysts spend hours writing SQL before they can ask a question about their data. Lumin lets them upload a file and ask in plain English. Claude API with schema-aware context injection generates answers and Vega-Lite charts inline. Multi-stage ingestion pipeline, multi-tenant PostgreSQL, weekly digest, PDF export.

**Munda — AI Crop Advisory Platform**
[GitHub](https://github.com/anesuruzvidzo1/munda) · [Live demo](https://munda-eight.vercel.app)

Smallholder farmers in Zimbabwe don't have agronomists on call. Munda gives them AI-powered crop diagnosis and yield advice instantly. Next.js 16, TypeScript strict mode, 170 passing tests, Drizzle ORM, Claude API with typed JSON response parsing. Multi-tenant PostgreSQL with Supabase Auth and row-level security.

**AI Farming Assistant**
[GitHub](https://github.com/anesuruzvidzo1/AI-Farming-Assistant)

Python REST backend, MongoDB, NOAA and Open-Meteo weather APIs, Random Forest and Gradient Boosting and Neural Network ensemble for crop recommendation and yield prediction. Deployed on AWS EC2.

**Cyber Anomaly Detection**
[GitHub](https://github.com/anesuruzvidzo1/cyber-anomaly-detection)

End-to-end pipeline ingesting NetFlow data, engineering per-host anomaly scores, and surfacing alerts through a Dockerized Streamlit dashboard with Elasticsearch and Kibana integration.

**AI News Summarizer**
[GitHub](https://github.com/anesuruzvidzo1/AI-News-Summarizer)

ETL pipeline with extractive summarization and TF-IDF and Logistic Regression article classification. Streamlit dashboard, MongoDB storage.

**Hospital Cost & Reimbursement Analysis**
[GitHub](https://github.com/anesuruzvidzo1/hospital-cost-analysis)

CMS cost-report data (2018-2022) enriched with county-level demographics. Interactive Tableau dashboard showing geographic reimbursement disparities across hospital types.

**SMS Application**
[GitHub](https://github.com/anesuruzvidzo1/SMS-Application)

Flask RESTful backend with JWT auth, asymmetric encryption for end-to-end message security, SQLite and SQLAlchemy with SQL injection protections.


## Let's Connect

[LinkedIn](https://linkedin.com/in/anesu-ruzvidzo-428193294) · [Email](mailto:anesuruzvidzo1@gmail.com)
