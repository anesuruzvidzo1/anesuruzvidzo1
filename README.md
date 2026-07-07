# Anesu Ruzvidzo

I build AI products end to end on the Anthropic Claude API. Retrieval pipelines with vector search and BM25, LLM observability infrastructure that traces every production call, agentic tool use systems that combine structured data and document retrieval. All shipped full stack with FastAPI, async PostgreSQL, and Next.js. Chicago based. Open to AI Engineer and Full Stack Engineer roles in Canada and the United States. Eligible for the Global Talent Stream.

## Stack

`Anthropic Claude API` `Tool Use` `RAG` `Hybrid Search` `LLM Observability` `Prompt Engineering` `Agentic Systems`
`Elasticsearch` `pgvector` `Sentence Transformers`
`TypeScript` `Python` `Next.js` `React` `FastAPI` `Node.js`
`PostgreSQL` `Redis` `asyncpg` `Supabase` `Drizzle ORM` `Docker` `AWS`
`Pandas` `Scikit-learn` `Anomaly Detection` `OR-Tools` `Constraint Optimization` `Geospatial` `Leaflet` `GeoJSON` `PySpark` `Tableau` `Flask`

## Projects

**BasinIQ — Alberta Energy RAG System**
[GitHub](https://github.com/anesuruzvidzo1/basiniq) · [Live demo](https://basiniq-sigma.vercel.app)

Hybrid retrieval over AER regulatory directives and Alberta well license data. Elasticsearch BM25 and pgvector dense search merged via Reciprocal Rank Fusion, reranked by a cross encoder. Claude tool use loop with two tools wired in: SQL over well data and document search over 392 indexed directive chunks. Session history persisted in PostgreSQL JSONB. Next.js 16 frontend with grouped source citations.

**ClosureIQ — Alberta Well Closure Planning**
[GitHub](https://github.com/anesuruzvidzo1/closureiq) · [Live demo](https://closureiq.vercel.app)

Reads Alberta's public well data and builds the lowest cost plan to meet Directive 088 closure quotas. Parses the AER inactive well inventory, scores each well by compliance and dormancy, estimates liability as a labelled cost band, and runs a Google OR-Tools constraint optimizer that selects which wells to close under a budget, batching by field area to cut mobilization cost. Next.js dashboard with a budget slider comparing the optimized plan to a naive priority baseline.

**FlareIQ — Alberta Flaring and Venting Intelligence**
[GitHub](https://github.com/anesuruzvidzo1/flareiq) · [Live demo](https://flareiq-vert.vercel.app)

Independent flaring and venting intelligence covering every Alberta operator, built from public Petrinex volumetric data. ETL over 53 monthly files into per facility flare, vent, and production series. Anomaly detection grounded in AER Directive 060 thresholds with a methane weighted CO2e severity score, an Isolation Forest for multivariate outliers, and temporal upset detection. Alberta Township System land descriptions converted to latitude and longitude, rendered as an interactive Next.js and Leaflet dashboard with a searchable operator watchlist.

**Argus — LLM Observability Platform**
[GitHub](https://github.com/anesuruzvidzo1/argus) · [Live demo](https://argus-dashboard-phi.vercel.app)

Wrapper around the Anthropic SDK that traces every production call with zero application code changes. Captures tokens, cost, latency, tool calls, and errors per session. FastAPI backend, asyncpg, PostgreSQL for trace storage, Redis pub/sub for fan-out, Next.js 15 dashboard via SSE. Deployed on Railway and Vercel.

**Lumin — AI Data Analysis Platform**
[GitHub](https://github.com/anesuruzvidzo1/lumin) · [Live demo](https://lumin-tau.vercel.app)

Claude reads the uploaded data schema and generates SQL, plain English answers, and Vega-Lite charts inline. Staged ingestion pipeline, multi tenant PostgreSQL, weekly email digest with Resend, PDF export. Drizzle ORM, Supabase Auth, 170 passing tests.

**Munda — AI Crop Advisory Platform**
[GitHub](https://github.com/anesuruzvidzo1/munda) · [Live demo](https://munda-eight.vercel.app)

AI crop diagnosis and yield advisory for Zimbabwean smallholder farmers. Claude API with typed JSON response parsing for structured agronomic recommendations. Next.js 16, TypeScript strict mode, 170 passing tests, Drizzle ORM, multi tenant PostgreSQL with Supabase Auth and row level security.

**AI Farming Assistant**
[GitHub](https://github.com/anesuruzvidzo1/AI-Farming-Assistant)

Python REST backend, MongoDB, NOAA and Open-Meteo weather APIs, Random Forest and Gradient Boosting and Neural Network ensemble for crop recommendation and yield prediction. Deployed on AWS EC2.

**Cyber Anomaly Detection**
[GitHub](https://github.com/anesuruzvidzo1/cyber-anomaly-detection)

End to end pipeline ingesting NetFlow data, engineering per host anomaly scores, and surfacing alerts through a Dockerized Streamlit dashboard with Elasticsearch and Kibana integration.

**AI News Summarizer**
[GitHub](https://github.com/anesuruzvidzo1/AI-News-Summarizer)

ETL pipeline with extractive summarization and TF-IDF and Logistic Regression article classification. Streamlit dashboard, MongoDB storage.

**Hospital Cost and Reimbursement Analysis**
[GitHub](https://github.com/anesuruzvidzo1/hospital-cost-analysis)

CMS cost report data (2018-2022) enriched with county-level demographics. Interactive Tableau dashboard showing geographic reimbursement disparities across hospital types.

**SMS Application**
[GitHub](https://github.com/anesuruzvidzo1/SMS-Application)

Flask RESTful backend with JWT auth, asymmetric encryption for end to end message security, SQLite and SQLAlchemy with SQL injection protections.

## Let's Connect

[LinkedIn](https://linkedin.com/in/anesu-ruzvidzo-428193294) · [Email](mailto:anesuruzvidzo1@gmail.com)
