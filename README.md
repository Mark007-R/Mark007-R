# Mark Rodrigues

AI/ML engineer. I build multi-agent systems, RAG pipelines, and production ML — with a bias for honest evaluation: held-out sets the agents never see, temporal splits that kill inflated numbers, and claims backed by measurements.

[LinkedIn](https://www.linkedin.com/in/markrodrigues07) · [Portfolio](https://mark007-r.github.io) · [Kaggle](https://kaggle.com/markoliverrodrigues) · [LeetCode](https://leetcode.com/Mark_Rodrigues) · markrodrigues2689@gmail.com

## Flagship work

**[CrewML](https://github.com/Mark007-R/CrewML)**
An autonomous multi-agent ML engineering crew built on LangGraph. Give it a raw tabular dataset and a task; specialised agents profile the data, plan an approach, engineer features, train, critique, and report. Every run is scored against a held-out evaluation the agents never touch, so the crew can't grade its own homework.

**[Fraud-Detection-MLOps](https://github.com/Mark007-R/Fraud-Detection-MLOps)**
Payment fraud detection where the real claim is MLOps discipline, not model quality. An upgrade sprint found and fixed a data-leakage bug that had been inflating the headline AUC, then layered MLflow registry promotion/rollback, KS+PSI drift detection, auto-retrain, and Dask-deterministic feature engineering on top of a DVC pipeline. [Live demo](https://iambatman07-sentinel.hf.space)

**[Diagram-Structure-Extractor](https://github.com/Mark007-R/Diagram-Structure-Extractor)**
Takes an architecture-diagram image and emits schema-valid JSON — every component, arrow, icon, and relationship. Strict-parseable output on 15 of 15 benchmark diagrams, because results are typed Pydantic models validated by construction rather than free-form LLM text. [Live API](https://iambatman07-diagramine.hf.space)

**[Restaurant-Intelligence-Platform](https://github.com/Mark007-R/Restaurant-Intelligence-Platform)**
Sentiment, complaint classification, and RAG chat over customer reviews. A 7-day sprint replaced two components that looked like ML but weren't, measured the replacements against real eval sets, and shipped the winners behind FastAPI + Redis + Docker without breaking a single existing call site. [Live demo](https://iambatman07-restoai.hf.space)

**[AI-Data-Analyst](https://github.com/Mark007-R/AI-Data-Analyst)**
Upload a CSV or XLSX and get auto-generated charts, a written summary, and a chatbot that answers with real SQL executed through a custom MCP server — no hallucinated numbers. FastAPI + DuckDB + ECharts.

## More projects

| Project | What it does |
| --- | --- |
| [Semantic-Movie-Recommender](https://github.com/Mark007-R/Semantic-Movie-Recommender) | Semantic + multimodal recommendation over a 9,826-film TMDB catalog — transformer embeddings with Milvus/FAISS HNSW retrieval |
| [Document-QA-RAG](https://github.com/Mark007-R/Document-QA-RAG) | Production-ready RAG for PDF Q&A — Flask, FAISS, LangChain, Groq Llama 3 ([demo](https://iambatman07-ragleo.hf.space)) |
| [Code-Review-Agent](https://github.com/Mark007-R/Code-Review-Agent) | AI code review returning structured JSON findings with severity ratings and line-specific fixes ([demo](https://iambatman07-questagent.hf.space)) |
| [AI-Personal-Finance-Manager](https://github.com/Mark007-R/AI-Personal-Finance-Manager) | Finance tracking with a document-AI bill scanner ([demo](https://iambatman07-fintrack.hf.space)) |
| [Road-Safety-Analyzer](https://github.com/Mark007-R/Road-Safety-Analyzer) | India road-accident analytics: severity prediction, fatality forecasting, safer-route planning ([demo](https://iambatman07-saferouteanalyzer.hf.space)) |
| [Stock-Price-Forecaster](https://github.com/Mark007-R/Stock-Price-Forecaster) | LSTM stock prediction with live news and sentiment analysis ([demo](https://iambatman07-stockai.hf.space)) |
| [Product-Recommendation-Engine](https://github.com/Mark007-R/Product-Recommendation-Engine) | Collaborative + content-based recommender with popularity fallback ([demo](https://iambatman07-shopsenseai.hf.space)) |
| [Cricket-Cover-Drive-Analyzer](https://github.com/Mark007-R/Cricket-Cover-Drive-Analyzer) | Real-time cover-drive biomechanics from video via MediaPipe pose estimation |
| [Crypto-Sentiment-Analysis](https://github.com/Mark007-R/Crypto-Sentiment-Analysis) | How the Fear & Greed Index shapes trader performance, on historical Hyperliquid data |

All repositories: [github.com/Mark007-R](https://github.com/Mark007-R?tab=repositories)

## Stack

Python · PyTorch · TensorFlow · scikit-learn · XGBoost · LangChain / LangGraph · sentence-transformers · FAISS / Milvus / ChromaDB · FastAPI · Flask · Streamlit · MLflow · DVC · Docker · MySQL / PostgreSQL · GitHub Actions
