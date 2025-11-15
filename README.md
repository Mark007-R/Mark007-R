<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=markrodrigues&label=Profile%20views&color=0e75b6&style=flat)

# 👋 Hello, I'm Mark Rodrigues

[![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=Computer+Engineering+Student+🎓;Full-Stack+Developer+💻;Data+Scientist+%26+AI+Engineer+🤖;Building+RAG+Systems+%26+ML+Solutions+🚀&center=true&width=600&height=50&color=58A6FF&vCenter=true&size=22)](https://git.io/typing-svg)

</div>

<div align="center">
  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mark-rodrigues-507223266/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:markrodrigues2004@gmail.com)
[![LeetCode](https://img.shields.io/badge/-LeetCode-FFA116?style=for-the-badge&logo=LeetCode&logoColor=black)](https://leetcode.com/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/markrodrigues)

📍 Mumbai, India | 🎓 St. Francis Institute of Technology | 📅 Expected Graduation: May 2026

</div>

---

## 🚀 About Me

```python
class MarkRodrigues:
    def __init__(self):
        self.education = "B.E. Computer Engineering (GPA: 7.8/10.0)"
        self.university = "St. Francis Institute of Technology, Borivli"
        self.location = "Mumbai, India 🇮🇳"
        self.role = "Data Science & AI Enthusiast"
        self.currently_seeking = "Remote Internships in Data Science/AI"
        
    def expertise(self):
        return {
            "AI_ML": ["RAG Systems", "LLMs", "NLP", "Deep Learning", "Computer Vision"],
            "Development": ["Flask", "REST APIs", "Web Scraping", "Full-Stack"],
            "Data_Science": ["Predictive Modeling", "Financial Analytics", "Sentiment Analysis"],
            "Databases": ["MySQL", "FAISS", "Vector DBs"]
        }
    
    def current_focus(self):
        return [
            "🤖 Building RAG-powered applications",
            "📊 Stock market prediction with LSTM",
            "💡 LLM-based intelligent systems",
            "🔍 Semantic search & embeddings"
        ]
    
    def fun_fact(self):
        return "I turn PDFs into conversations and CSVs into insights! 📄➡️💬"

me = MarkRodrigues()
print(me.fun_fact())
```

---

## 💼 Tech Stack

<div align="center">

### 👨‍💻 Programming Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### 🧠 AI/ML & Data Science
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

### 🔥 Frameworks & Tools
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

### 🗄️ Databases & Vector Stores
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-00599C?style=for-the-badge&logo=meta&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)

### 🛠️ Developer Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

</div>

---

## 🎯 Featured Projects

### 🍽️ 1. Restaurant Review Analysis & RAG Chat System
> **AI-powered restaurant review analysis with semantic search and sentiment analysis**

<details>
<summary>📋 View Details</summary>

**Description:** Aggregates reviews from multiple CSV datasets (Zomato, Google Reviews, Mumbai Aires), performs VADER sentiment analysis, and enables natural-language Q&A through RAG-based chat system.

**Key Features:**
- 🔄 Multi-source CSV integration with intelligent parsing (5+ formats)
- 😊 VADER sentiment analysis with complaint categorization (8 categories)
- 🔍 Semantic search using FAISS + SentenceTransformers (all-MiniLM-L6-v2, 384 dimensions)
- 📊 9 advanced visualizations (sentiment distribution, heatmaps, trend analysis)
- 🤖 AI-generated actionable recommendations with priority levels
- 🕷️ Web scraping fallback with parallel processing
- ✅ Review quality scoring and deduplication
- 💾 Persistent FAISS index with auto save/load

**Tech Stack:**
```
Flask | SQLAlchemy | FAISS | SentenceTransformers | VADER Sentiment
NLTK | Pandas | Matplotlib | Seaborn | BeautifulSoup4
```

[![Repo](https://img.shields.io/badge/GitHub-Repository-blue?style=flat&logo=github)](https://github.com/markrodrigues/Smart_Restaurant_System)

</details>

---

### 📄 2. RAG Document Q&A System
> **Retrieval-Augmented Generation web app powered by Llama 3 and Groq API**

<details>
<summary>📋 View Details</summary>

**Description:** Upload PDFs, automatically extract and chunk text, and perform natural-language question answering grounded in uploaded content using Llama 3 via Groq API.

**Key Features:**
- 📤 PDF upload with automatic text extraction and recursive chunking
- 🧩 PyPDF2 + RecursiveCharacterTextSplitter for optimal chunking
- 🔤 Semantic embeddings using SentenceTransformers (all-MiniLM-L6-v2)
- ⚡ FAISS indexing for fast cosine-similarity retrieval
- 🔗 Complete RAG workflow with LangChain + Groq's Llama 3 API
- 🌐 REST API endpoints (upload, list, query, delete, health checks)
- 💾 Persistent FAISS index storage with safe file handling
- 🔐 Environment-based configuration with GROQ_API_KEY

**Tech Stack:**
```
Flask | LangChain | Groq API (Llama 3) | SentenceTransformers
FAISS | PyPDF2 | python-dotenv
```

[![Repo](https://img.shields.io/badge/GitHub-Repository-blue?style=flat&logo=github)](https://github.com/markrodrigues/RAG_LEO)

</details>

---

### 💰 3. Personal Finance Management System
> **Track transactions, extract bills from PDFs, and get AI-powered investment recommendations**

<details>
<summary>📋 View Details</summary>

**Description:** Web-based personal finance management with user authentication, transaction CRUD operations, and automated bill processing with regex-based extraction.

**Key Features:**
- 🔐 User authentication with Flask sessions & Werkzeug password hashing
- 💳 Transaction management (add/delete) with MySQL storage
- 📄 PDF bill extraction using Poppler's pdftotext with regex pattern matching
- 💡 Investment recommendation engine for multiple financial products
- 🏦 Queries Recurring Deposits, Bonds, Bank Stocks, Life Insurance based on balance
- ⚙️ Automated transaction insertion from extracted bill data
- 🧩 Modular blueprint-based architecture for scalability

**Tech Stack:**
```
Flask | PyMySQL | MySQL | Werkzeug | Poppler (pdftotext)
regex | Flask Blueprints
```

[![Repo](https://img.shields.io/badge/GitHub-Repository-blue?style=flat&logo=github)](https://github.com/markrodrigues/Personal_Finance_Manager)

</details>

---

### 📈 4. Stock Price Predictor & Technical Analysis
> **LSTM-powered stock forecasting with real-time news sentiment and correlation analysis**

<details>
<summary>📋 View Details</summary>

**Description:** AI-powered stock market analysis platform leveraging LSTM neural networks for price forecasting, integrated with real-time news sentiment analysis and multi-stock correlation.

**Key Features:**
- 🧠 LSTM-based prediction with 60-day lookback windows (1-100 day forecasts)
- 🏗️ Dual-layer LSTM architecture (50 units, 20% dropout, 10 epochs)
- 📊 Technical indicators: SMA50, EMA20, Bollinger Bands
- 📉 Interactive candlestick charts with Plotly
- 📰 Real-time news sentiment analysis using VADER (5 latest articles)
- 🔗 Stock correlation dashboard with Pearson heatmaps
- 🌐 Alpha Vantage API with intelligent caching (1hr historical, 5min quotes)
- ⚠️ Rate limit handling (25 requests/day)
- 📏 MinMaxScaler normalization with 80/20 train-test split
- 💾 CSV export for predictions
- 🗂️ Multi-page navigation (Predictor, Historical, Correlation)

**Tech Stack:**
```
Streamlit | TensorFlow/Keras | Alpha Vantage API | NewsAPI
scikit-learn | VADER Sentiment | Plotly | Matplotlib | Seaborn
Pandas | NumPy
```

[![Repo](https://img.shields.io/badge/GitHub-Repository-blue?style=flat&logo=github)](https://github.com/markrodrigues/Stock_Price_Predictor)

</details>

---

## 🏆 Certifications

<div align="center">

| 📜 Certification | 🏢 Issuer | 🔗 Platform |
|:----------------|:----------|:------------|
| **Intermediate Machine Learning** | Kaggle | ![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white) |
| **Advanced SQL** | Kaggle | ![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white) |
| **Exploratory Data Analysis & Visualization** | Scaler | ![Scaler](https://img.shields.io/badge/Scaler-FF6B35?style=flat) |
| **Deloitte Data Analytics Job Simulation** | Forage | ![Forage](https://img.shields.io/badge/Forage-1B1B1B?style=flat) |
| **Generative AI: Working with Large Language Models** | LinkedIn | ![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white) |

</div>

---

## 📊 GitHub Statistics

<div align="center">
  
<img width="49%" src="https://github-readme-stats.vercel.app/api?username=markrodrigues&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" />
<img width="49%" src="https://streak-stats.demolab.com/?user=markrodrigues&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" />

<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=markrodrigues&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" />
<img width="49%" src="https://github-readme-activity-graph.vercel.app/graph?username=markrodrigues&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=58A6FF&line=58A6FF&point=C9D1D9" />

</div>

---

## 🏆 GitHub Trophies

<div align="center">
  
![trophy](https://github-profile-trophy.vercel.app/?username=markrodrigues&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4&column=7)

</div>

---

## 💡 Skills Overview

```yaml
Machine_Learning:
  - Regression, Classification, Random Forests, XGBoost
  - Deep Learning: ANN, CNN, RNN, LSTM
  - NLP: VADER Sentiment, SentenceTransformers, RAG
  - LLMs: Llama 3, Groq API, LangChain
  - Computer Vision: OpenCV, MediaPipe

Data_Science:
  - Data Visualization: Tableau, Power BI, Plotly, Seaborn, Matplotlib
  - Data Cleaning & Preprocessing
  - Feature Engineering
  - Exploratory Data Analysis

Development:
  - Backend: Flask, REST APIs, SQLAlchemy, Blueprints
  - Frontend: HTML, CSS, JavaScript
  - Version Control: Git, GitHub
  - Databases: MySQL, PyMySQL

Soft_Skills:
  - Effective Communication
  - Team Collaboration
  - Problem Solving
```

---

## 🎓 Education

**Bachelor of Engineering (Computer Engineering)**  
📍 St. Francis Institute of Technology, Borivli  
📅 Expected Graduation: May 2026  
📊 GPA: 7.8/10.0

**HSC (Computer Science)**  
📍 Shri T.P. Bhatia College, Kandivli  
📅 Completed: June 2022

---

## 📫 Let's Connect!

<div align="center">

💼 **Open to Remote Internships in Data Science & AI**

I'm passionate about building intelligent systems that solve real-world problems. Whether it's RAG systems, predictive analytics, or full-stack applications, I love turning complex data into actionable insights.

[![LinkedIn](https://img.shields.io/badge/Let's_Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mark-rodrigues-507223266/)
[![Email](https://img.shields.io/badge/Send_me_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:markrodrigues2004@gmail.com)

---

### 💬 "Data is the new oil, but AI is the engine that powers it!"

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>

</div>
