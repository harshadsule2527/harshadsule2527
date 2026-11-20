# Hi, I'm Harsh 👋

**AI Developer @ TCS · Building voice AI agents that hold up in real phone calls**

I build multilingual, speech-to-speech AI agents for enterprise IT support: real callers, real phone lines, real tools behind them. Most of my day is making voice bots behave in production: cutting latency, killing hallucinated speech, fixing barge-in, and debugging from live call logs.

📍 Mumbai, India · 💼 Open to **Voice AI / Conversational AI / Applied AI Engineer** roles

---

### 🎙️ What I'm working on

- **Enterprise voice agent (TCS)**: a Level-1 IT service desk agent on **Azure OpenAI Realtime + FastAPI + WebSockets**, reachable over Genesys telephony and the browser. It calls **18 tools** (ticketing, knowledge base search, remote remediation, OTP-verified password and MFA resets, onboarding) and hands off to human agents.
  - Migrated the browser and telephony pipelines from the retired preview Realtime API to the **GA v1 protocol** with bot behaviour unchanged
  - Cut live-agent transfer delay from **~90s to immediate**; cleared 6 blocking defects in one day of log-driven debugging
  - Hardened for noisy calls: greeting noise gate, semantic VAD, Whisper hallucination filter, turn coalescing
  - Stopped mid-call language switching across English, Danish, German and Hindi
- **Leo** *(personal, in progress)*: my local-first, offline voice assistant. Wake word → faster-whisper → local LLM (Ollama) → Piper TTS, with tools, short/long-term memory and a permission gate. Happy to demo it.

### 🛠️ Tech I actually use

**Voice AI** &nbsp;
![Azure OpenAI Realtime](https://img.shields.io/badge/Azure_OpenAI_Realtime-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-412991?style=flat&logo=openai&logoColor=white)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat&logo=elevenlabs&logoColor=white)
![Piper TTS](https://img.shields.io/badge/Piper_TTS-555555?style=flat)

**LLMs & Agents** &nbsp;
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-Pinecone_·_FAISS-2E7D32?style=flat)

**Backend** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat&logo=socketdotio&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB_/_Cosmos_DB-47A248?style=flat&logo=mongodb&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)

**ML** &nbsp;
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-FF0D57?style=flat)

**Cloud** &nbsp;
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat&logo=azuredevops&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

### 📂 Selected projects

| Project | What it is | Stack |
|---|---|---|
| [Customer Behavior Prediction](https://github.com/harshadsule2527/API-model-for-Customer-Prediction-Application-) | Repeat-purchase prediction + SVD recommender behind a REST API | scikit-learn, Flask |
| [Home Price Prediction](https://github.com/harshadsule2527/Home-Price-Prediction-using-FRED-API) | Macro time-series regression, explained with SHAP | FRED API, Random Forest, SHAP |
| [AI Resume Analyzer](https://github.com/harshadsule2527/AI-Based-Resume-Analuzer) | Resume analysis and job matching with RAG | LangChain, FAISS, OpenAI, Streamlit |
| [AI Sales Agent](https://github.com/harshadsule2527/AI-Sales-Agent-Project) | Fine-tuned distilgpt2 for sales conversations | PyTorch, Transformers |

### 🎓 Background

BSc Computer Science (AI & ML) · Certified: Azure AZ-900, OCI Foundations, ML in Production (Coursera)

### 📫 Reach me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harsh-adsule-m2527)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:harshadsule27@gmail.com)
