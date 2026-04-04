<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:1a1a3e,100:0f2027&height=180&section=header&text=Muhammad%20Saim%20Khalid&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%E2%80%94%20LLM%20Applications%20%7C%20RAG%20Systems%20%7C%20Generative%20AI&descSize=15&descAlignY=58&descColor=94a3b8" />

</div>

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saimkhalid/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saim.khalid983@gmail.com)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/saimcodes)
[![Open to Work](https://img.shields.io/badge/Open%20to%20Work-22c55e?style=for-the-badge&logo=checkmarx&logoColor=white)](#-lets-connect)

</div>

---

## 👋 Who I Am

I'm an **AI Engineer** from Pakistan who builds complete, working AI systems — from the RAG pipeline to the frontend UI. My focus is on **LLM applications that solve real business problems**: automating procurement workflows, optimizing logistics, and making domain knowledge instantly queryable through conversational AI.

I work across the full AI stack: vector search, LLM orchestration, API design, and interactive frontends. Every project I ship has a real use case behind it.

- 🔭 **Building:** Production LLM apps with RAG, agents, and real-world integrations
- 🧠 **Specializing in:** OpenAI APIs, FastAPI, ChromaDB, FAISS, OSRM, Genetic Algorithms
- 🌍 **Location:** Pakistan — open to remote roles worldwide
- 💼 **Status:** Actively looking for AI / ML Engineer roles

---

## 🚀 Projects

> Real systems. Real code. Click the repo links to see for yourself.

---

### 📄 [Smart RFP System](https://github.com/SaimKhalid388/smart-rfp-system) — AI Procurement Intelligence Platform

Procurement teams spend hours reading vendor proposals, copying data into spreadsheets, and struggling to compare apples to oranges. This system automates the entire proposal evaluation lifecycle.

**How it works:**
- Upload any RFP PDF → AI extracts requirements, deadlines, and proposal form structure
- Vendors submit proposals → AI parses pricing, timelines, experience, materials, and warranties automatically
- Dynamic comparison matrix aligns every vendor's data row-by-row against RFP requirements
- Chat with proposals in natural language: *"Which vendor has the shortest delivery timeline?"*
- Radar charts and AI-scored rankings surface the best-fit vendor

**Stack:**
`React` `Vite` `TailwindCSS` `FastAPI` `Python` `GPT-4o` `text-embedding-3-large` `ChromaDB` `SQLite` `ApexCharts`

**Technical highlights:**
- Vector embeddings (3072-dim) stored in ChromaDB for semantic proposal search
- Groq fallback if OpenAI is unavailable — production resilience built in
- Full-stack app: React frontend + FastAPI backend with auto-generated `/docs`
- Clean layered architecture: routers → services → agents

---

### 🚌 [VRP — Multi-Depot Employee Transport Optimizer](https://github.com/SaimKhalid388/VRP)

A real Vehicle Routing Problem solver for a concrete use case: shuttling employees from multiple depots to a factory across shifts, using a heterogeneous fleet (company-owned + rented vehicles).

**How it works:**
- Define depots, factory location, shift times, and fleet via CLI or the web interface
- Genetic Algorithm solves the routing problem with a deterministic feasibility decoder
- Routes are computed on **real roads** via OSRM — not straight-line estimates
- Solution visualized as an interactive Folium map with per-route tooltips (passengers, cost, time, distance)

**Stack:**
`Python` `FastAPI` `React` `Genetic Algorithm` `OSRM` `Folium` `Leaflet.js`

**Technical highlights:**
- Heterogeneous fleet: respects owned vehicle counts, handles rented vehicles with fixed costs
- Greedy nearest-neighbor multi-stop pickup with hard capacity enforcement
- OSRM segment caching — avoids redundant API calls, critical at scale
- Interactive Leaflet map picker for placing factory and depot coordinates
- Dual-mode: CLI for engineers, full web UI for non-technical stakeholders

---

### 🥐 [Bakery Chat — Domain-Specific RAG Chatbot](https://github.com/SaimKhalid388/BAKERY-CHAT)

A full-stack conversational AI system for a bakery business, answering queries about menu items, locations, and FAQs using a complete RAG pipeline — not just a prompt-stuffed chatbot.

**How it works:**
- Bakery knowledge base indexed with FAISS (vector search) and Whoosh (full-text search)
- User query triggers: retrieval → reranking → prompt construction → LLM generation → postprocessing
- Multi-turn session management maintains conversation context across messages
- Clean React frontend with a high-performance FastAPI backend

**Stack:**
`Python` `FastAPI` `React` `FAISS` `Whoosh` `Groq API` `Uvicorn` `Pydantic`

**Technical highlights:**
- **Hybrid retrieval:** combines FAISS vector similarity with Whoosh keyword search for better recall
- Full pipeline with reranking and postprocessing — not just naive retrieval
- Session management for genuine multi-turn conversations
- Production-ready structure: separate backend/frontend, `.env` config, clean layout

---

## 🛠️ Tech Stack

**AI & Language Models**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)

**Vector Search & RAG**

![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logoColor=white)
![Whoosh](https://img.shields.io/badge/Whoosh%20Full--Text-6B7280?style=flat-square&logoColor=white)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Uvicorn](https://img.shields.io/badge/Uvicorn-4B8BBE?style=flat-square&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Geospatial & Optimization**

![OSRM](https://img.shields.io/badge/OSRM%20Real--Road%20Routing-7D3C98?style=flat-square&logoColor=white)
![Folium](https://img.shields.io/badge/Folium-77B829?style=flat-square&logo=leaflet&logoColor=white)
![Genetic Algorithm](https://img.shields.io/badge/Genetic%20Algorithm-0f766e?style=flat-square&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📊 GitHub Activity

> Contributions, streaks, and languages — the real signal of an active engineer.

<div align="center">

<!-- Overall Stats + Top Languages side by side -->
<img height="170" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=SaimKhalid388&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=818cf8&text_color=e2e8f0&icon_color=818cf8" />
<img height="170" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=SaimKhalid388&theme=tokyonight&layout=compact&hide_border=true&bg_color=0d1117&title_color=818cf8&text_color=e2e8f0&langs_count=8" />

</div>

<div align="center">

<!-- Streak Stats -->
<img width="70%" src="https://github-readme-streak-stats.herokuapp.com/?user=SaimKhalid388&theme=tokyonight&hide_border=true&background=0d1117&stroke=818cf8&ring=818cf8&fire=a78bfa&currStreakLabel=e2e8f0&sideLabels=e2e8f0&dates=94a3b8&currStreakNum=ffffff&sideNums=ffffff" />

</div>

<div align="center">

<!-- Contribution Activity Graph -->
<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=SaimKhalid388&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=818cf8&line=818cf8&point=a78bfa&area=true&area_color=818cf8" />

</div>

<div align="center">

<!-- Trophy shelf -->
<img width="95%" src="https://github-profile-trophy.vercel.app/?username=SaimKhalid388&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8" />

</div>

---

## 🧩 What I Bring to a Team

| Capability | Evidence |
|---|---|
| **Full-stack AI apps** | All three projects ship a React frontend + FastAPI backend — not just Jupyter notebooks |
| **RAG pipeline design** | Bakery Chat: hybrid FAISS + Whoosh retrieval with reranking; Smart RFP: ChromaDB + GPT-4o embeddings (3072-dim) |
| **LLM orchestration** | Structured PDF extraction, multi-turn chat, fallback provider logic (OpenAI → Groq) |
| **Optimization & algorithms** | Genetic Algorithm VRP solver with real-road OSRM routing and feasibility enforcement |
| **API design** | Clean FastAPI services with Pydantic validation, session management, auto-generated docs |
| **Domain adaptation** | Applied LLMs across procurement (RFP), logistics (VRP), and retail (Bakery) — three different industries |
| **Production thinking** | API caching, provider fallbacks, `.env` config, modular project structure, UIs for non-technical users |

---

## 💬 How I Think About AI Engineering

I start with the real-world problem, not the technology. The three projects above came from genuine pain points:

- **Smart RFP** → Procurement teams manually copying vendor data from PDFs into Excel for hours
- **VRP** → Fleet managers routing employee transport on intuition instead of optimized paths
- **Bakery Chat** → Small businesses unable to offer 24/7 customer support without hiring staff

The right question is always *"What does the user actually need?"* — not *"What AI can I apply here?"* That's the engineering judgment I bring to every project.

---

## 📬 Let's Connect

I'm actively looking for **AI Engineer**, **LLM Developer**, or **ML Engineer** roles — remote or Pakistan-based.

If you're building something in the AI space and need someone who ships complete, working systems, let's talk.

**📧** [saim.khalid983@gmail.com](mailto:saim.khalid983@gmail.com)  
**🔗** [linkedin.com/in/saimkhalid](https://www.linkedin.com/in/saimkhalid/)

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:1a1a3e,100:0f0c29&height=100&section=footer" />

*"Build AI systems that earn trust — with real code, real data, and real results."*

</div>
