<div align="center">

<img src="./ai-banner.png" width="100%" />

# SANKET BIRADAR

### AI Engineer | GenAI Engineer

Building production-ready Generative AI and backend systems with Python, FastAPI, LLMs and AI Agents.

<p>
<a href="https://github.com/SanketBiradar017">
<img src="https://img.shields.io/badge/GitHub-SanketBiradar017-181717?style=for-the-badge&logo=github"/>
</a>
<a href="https://www.linkedin.com/in/sanket_biradar">
<img src="https://img.shields.io/badge/LinkedIn-Sanket_Biradar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:sanketbiradar007@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
</p>

📍 Bangalore, India

</div>

---

## 👨‍💻 Professional Summary

AI/GenAI Engineer with **experience in** building and deploying production-grade Generative AI and backend systems using **Python and FastAPI**.

Hands-on experience developing **RAG pipelines, LLM applications, LangChain, LangGraph, multi-agent systems, agent orchestration, and vector search solutions**.

Experienced in designing **scalable asynchronous APIs, real-time AI applications, background processing, caching, and cloud deployments on Google Cloud Platform (GCP)**.

Strong focus on **LLM orchestration, backend architecture, performance optimization, and production-ready AI systems**.

---

## 🧠 Core Skills

### 💻 Programming

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
</p>

### ⚡ Backend Engineering

<p>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/REST_APIs-02569B?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Async_APIs-3776AB?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Microservices-6A5ACD?style=for-the-badge"/>
</p>

### 🤖 Generative AI

<p>
<img src="https://img.shields.io/badge/LLM_Applications-412991?style=for-the-badge"/>
<img src="https://img.shields.io/badge/RAG-6A5ACD?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Prompt_Engineering-8A2BE2?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LLM_Orchestration-5C2D91?style=for-the-badge"/>
</p>

### 🔗 AI Frameworks

<p>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LlamaIndex-000000?style=for-the-badge"/>
</p>

### 🧠 Agent Systems

<p>
<img src="https://img.shields.io/badge/Multi--Agent_Systems-6A5ACD?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Agent_Routing-412991?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Agent_Orchestration-5C2D91?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Tool_Calling-8A2BE2?style=for-the-badge"/>
</p>

### 🗄️ Databases & Performance

<p>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge"/>
</p>

**Also:** Vector Databases • Background Jobs • Caching • Async Processing

### ☁️ Cloud & Deployment

<p>
<img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/>
</p>

### 📐 Architecture

**Scalable Systems • Microservices • API Architecture • RAG Pipelines**

### 📊 Libraries & Developer Tools

<p>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
</p>

---

# 🧠 AI Engineering Architecture

```text
                              ┌─────────────────┐
                              │      USERS      │
                              └────────┬────────┘
                                       │
                                       ▼
                              ┌─────────────────┐
                              │     FastAPI     │
                              │     Gateway     │
                              └────────┬────────┘
                                       │
                                       ▼
                              ┌─────────────────┐
                              │    LangGraph    │
                              │  Agent Engine   │
                              └────────┬────────┘
                                       │
                  ┌────────────────────┼────────────────────┐
                  │                    │                    │
                  ▼                    ▼                    ▼
           ┌─────────────┐      ┌─────────────┐      ┌─────────────┐
           │    LLMs     │      │   RAG /     │      │  PostgreSQL │
           │             │      │ Vector DB   │      │   / MySQL   │
           │ OpenAI      │      │             │      │             │
           │ Gemini      │      │ Retrieval   │      │ State/Data  │
           │ Ollama      │      │ Embeddings  │      │             │
           └─────────────┘      └─────────────┘      └─────────────┘
                  │
                  ▼
           ┌─────────────┐
           │    Redis    │
           │ Cache/Queue │
           └─────────────┘
                  │
                  ▼
           ┌─────────────┐
           │   Celery    │
           │ Background  │
           │    Jobs     │
           └─────────────┘
