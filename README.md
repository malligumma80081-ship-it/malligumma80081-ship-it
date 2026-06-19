<div align="center">

<!-- Animated header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,100:3b82f6&height=200&section=header&text=Mallikarjuna%20Rao%20Gumma&fontSize=40&fontColor=ffffff&fontAlignY=38&desc=Senior%20AI%20Developer%20%7C%20LLM%20%7C%20RAG%20%7C%20FastAPI&descAlignY=58&descSize=18" />

<!-- Typing animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=06B6D4&center=true&vCenter=true&width=600&lines=Building+Production-Grade+AI+Systems;LLM+%2B+RAG+%2B+FastAPI+Specialist;Anthropic+Claude+%26+OpenAI+GPT-4+Expert;End-to-End+ML+Pipeline+Engineer;Turning+Ideas+into+Intelligent+Products" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mallikarjuna-rao-gumma)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:malligumma77@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/malligumma80081-ship-it)
[![Location](https://img.shields.io/badge/Hyderabad-India-06b6d4?style=for-the-badge&logo=googlemaps&logoColor=white)](https://maps.google.com/?q=Hyderabad,India)

</div>

---

## 👨‍💻 About Me

> **Senior AI Developer** with **2+ years** building production-grade AI systems that actually ship.  
> I specialize in **LLM pipelines**, **RAG architectures**, and **async FastAPI microservices** — the full stack from prompt to production.

```python
mallikarjuna = {
    "role":       "Senior AI Developer / Python Backend Architect",
    "location":   "Hyderabad, Telangana, India",
    "company":    "Axiora Global Solutions.",
    "focus":      ["LLM Integration", "RAG Pipelines", "FastAPI", "MLOps"],
    "apis":       ["Anthropic Claude API", "OpenAI GPT-4"],
    "currently_learning": [
        "End-to-end ML pipelines (sklearn → SHAP → MLflow → FastAPI)",
        "FastAPI + RAG + Agent UI with WebSocket streaming",
        "Model drift monitoring & SHAP explainability",
    ],
    "passion":    "Building AI systems that are observable, maintainable, production-ready",
}
```

---

## 🚀 What I'm Building Right Now

> Projects from my **live learning sessions** — built today, production-ready tomorrow.

### 🩺 Medical AI Assistant — FastAPI + RAG + Agent + WebSocket
> Full-stack AI assistant with 3 modes: RAG query, Agent tool dispatch, and live streaming

**Stack:** FastAPI · OpenAI GPT-4 · ChromaDB · WebSocket · Pydantic v2 · aiofiles · HTML/JS

```
📁 medical-ai/
├── main.py              ← FastAPI app, CORS, WebSocket streaming (/ws/stream)
├── routers/
│   ├── rag.py           ← Async RAG: embed → vector retrieve → GPT-4o generate
│   ├── agent.py         ← Agent loop: LLM tool dispatch (4 medical tools)
│   └── logger.py        ← BackgroundTasks + aiofiles audit log
└── static/index.html    ← Dark dashboard: RAG / Agent / Stream modes
```

**Key concepts demonstrated:**
- `APIRouter` + `CORSMiddleware` + `Pydantic BaseModel` validation
- Async RAG pipeline: keyword/vector retrieval → context-stuffed GPT prompt
- Agent loop: `tool_calls` → dispatch → feed result back → repeat (max 5 iter)
- `BackgroundTasks` + `aiofiles` — response returns instantly, logs write after
- WebSocket streaming — tokens appear word-by-word in the browser

---

### 📊 End-to-End ML Pipeline — Train → Evaluate → Serve
> Complete production ML workflow with explainability and a live REST API

**Stack:** scikit-learn · SHAP · MLflow · GridSearchCV · FastAPI · Pydantic v2

```
📁 ml-pipeline/
├── step1_pipeline.py         ← sklearn Pipeline: ColumnTransformer + RandomForest
├── step2_gridsearch_mlflow.py← GridSearchCV (45 fits) + MLflow experiment tracking
├── step3_shap.py             ← SHAP TreeExplainer: global + per-patient explanation
├── step4_model_registry.py   ← Model versioning: None→Staging→Production→Archived
├── step5_serve.py            ← FastAPI: /predict, /predict/batch, /monitor/drift
├── run_all.py                ← One command: train all steps → start API
└── static/index.html         ← Live dashboard: predict, batch, drift monitor, audit
```

**Key concepts demonstrated:**
- `Pipeline` + `ColumnTransformer` — zero data leakage, one fit/predict call
- `GridSearchCV` with `model__` prefix targeting Pipeline steps
- SHAP `TreeExplainer` — per-patient waterfall + global beeswarm
- Local model registry with stage promotion (mirrors MLflow)
- FastAPI drift endpoint — live input stats vs training baseline

---

## 💼 Professional Projects

### 🔍 LLM-Powered Document Q&A (RAG Platform)
**FastAPI · LangChain · OpenAI · Anthropic Claude · FAISS · ChromaDB · PostgreSQL · Docker**

- End-to-end RAG pipeline: document ingestion → OpenAI embeddings → FAISS vector search → GPT-4 answer
- Hybrid retrieval: dense vector search + metadata filtering for precision
- Sub-2s query latency under concurrent load; containerised with Docker
- Prompt templates engineered to minimize hallucination and maximize grounding

### 🏢 AI-Enabled Business Management Platform
**FastAPI · SQLAlchemy · Redis · Celery · Anthropic Claude · Pydantic v2 · Docker**

- Anthropic Claude API for NLP query parsing, analytics summaries, automated insight generation
- ML inference as Celery async background tasks with circuit-breaker + retry logic
- Redis caching layer cut repeated LLM API calls → **40% latency reduction**
- JWT auth, Pydantic v2 input sanitization, Alembic-versioned PostgreSQL

### 🍕 Food Delivery Platform — Backend Microservice
**FastAPI · PostgreSQL · SQLAlchemy · Alembic · Redis · AsyncIO · Docker**

- Full order lifecycle: users → menus → cart → orders with soft-delete + audit fields
- Redis rate-limiting + session caching; background tasks for notifications + invoices
- Circuit-breaker pattern for payment gateway resilience

---

## 🛠️ Tech Stack

<div align="center">

### AI / LLM
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-D4A017?style=for-the-badge&logo=anthropic&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI_GPT--4-412991?style=for-the-badge&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)

### Backend & Frameworks
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python_3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)

### ML & Data
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-FF6B35?style=for-the-badge&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### Databases & DevOps
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

</div>

---

## 📈 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=malligumma80081-ship-it&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=malligumma80081-ship-it&layout=compact&langs_count=8&theme=tokyonight"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=malligumma80081-ship-it&theme=tokyonight" alt="GitHub Streak" />
</div>

---

## 🏆 Key Achievements

| Metric | Impact |
|--------|--------|
| 🤖 Manual effort reduction | **~60%** via LLM automation pipelines |
| ⚡ Inference latency reduction | **~40%** via Redis caching on AI endpoints |
| 📈 LLM output quality improvement | **30%+** via advanced prompt engineering |
| 🔄 Query response latency | **< 2 seconds** under concurrent load |

---

## 📚 Certifications

- 🎓 **Data Analysis using Python** — Coursera / Great Learning
- 🎓 **Python & Django Full-Stack Development** — Priacc Innovations

---

## 📬 Let's Connect

<div align="center">

**Open to:** Senior AI/ML Engineer · LLM Engineer · Python Architect roles

[![Email](https://img.shields.io/badge/malligumma77@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:malligumma77@gmail.com)
[![Phone](https://img.shields.io/badge/+91_80081_28338-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+918008128338)

</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:3b82f6,100:06b6d4&height=100&section=footer"/>
</div>
