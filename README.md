
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1f6feb&height=120&section=header&reversal=false&animation=fadeIn" width="100%"/>

<h1>Muhammad Saim Khalid</h1>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=16&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=680&lines=AI+Engineer+%7C+LLM+Systems+%7C+Full-Stack+AI+Applications;Building+AI+that+solves+real+business+problems;RAG+%C2%B7+Optimization+%C2%B7+FastAPI+%C2%B7+React+%C2%B7+OpenAI" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=58A6FF)](https://www.linkedin.com/in/saimkhalid/)
[![Email](https://img.shields.io/badge/Gmail-0d1117?style=flat-square&logo=gmail&logoColor=58A6FF)](mailto:saim.khalid983@gmail.com)
[![Twitter](https://img.shields.io/badge/Twitter-0d1117?style=flat-square&logo=x&logoColor=58A6FF)](https://twitter.com/saimcodes)
[![Views](https://komarev.com/ghpvc/?username=SaimKhalid388&style=flat-square&color=1f6feb&label=Profile+Views&labelColor=0d1117)](https://github.com/SaimKhalid388)

</div>

---

I'm an **AI Engineer** from Pakistan 🇵🇰 who builds **complete, production-ready AI systems** — not prototypes, not notebooks. Three shipped projects, three industries, three real full-stack applications you can open right now.

| | |
|---|---|
| 🔭 **Building** | LLM-powered automation for enterprise workflows |
| 🧠 **Deepening** | Multi-agent systems, LLM fine-tuning, production RAG at scale |
| 💬 **Ask me about** | RAG pipelines, FastAPI, OpenAI APIs, vector search, system design |
| 📍 **Location** | Pakistan — open to remote roles worldwide |
| 💼 **Status** | **Actively looking** for AI / LLM / ML Engineer roles |
| 📬 **Contact** | [saim.khalid983@gmail.com](mailto:saim.khalid983@gmail.com) |

---

## Projects

> Real repos. Real code. Click and explore — the work speaks for itself.

<br/>

#### 📄 &nbsp;[Smart RFP System](https://github.com/SaimKhalid388/smart-rfp-system) &nbsp;·&nbsp; AI Procurement Platform

Procurement teams spend hours copying vendor proposal data from PDFs into spreadsheets. This eliminates that entirely.

**Workflow:** Upload an RFP PDF → AI extracts requirements and proposal form structure → vendors submit proposals → AI parses pricing, timelines, materials, warranties → side-by-side comparison matrix → radar charts + AI-scored vendor ranking. Chat with any proposal in natural language: *"Which vendor offers the shortest delivery timeline?"*

> **The engineering challenge:** Structured extraction from unstructured PDFs at scale. 3,072-dimensional embeddings in ChromaDB for semantic proposal search. Vendor data aligned column-by-column for a fair apples-to-apples comparison. Live Groq fallback if OpenAI goes down — it keeps working.

```
Stack: GPT-4o · text-embedding-3-large · ChromaDB · FastAPI · React · Vite · TailwindCSS · ApexCharts · SQLite
```

<br/>

#### 🚌 &nbsp;[VRP Optimizer](https://github.com/SaimKhalid388/VRP) &nbsp;·&nbsp; Multi-Depot Route Solver

Fleet managers routing employee shuttles on gut feel instead of math. This solves it.

**Workflow:** Define depots, factory, shifts, and fleet → Genetic Algorithm solves the routing problem → routes computed on **actual roads** via OSRM (not straight-line estimates) → interactive Folium map with per-route breakdown: passengers, cost, distance, time.

> **The engineering challenge:** VRP is NP-hard. The GA uses a deterministic feasibility decoder that simultaneously respects owned vehicle counts, rented vehicle fixed costs, shift arrival windows, and seat capacity. OSRM segment caching prevents redundant road API calls. Dual interface: CLI for engineers, full web app for non-technical operations teams.

```
Stack: Python · Genetic Algorithm · OSRM · FastAPI · React · Folium · Leaflet.js
```

<br/>

#### 🥐 &nbsp;[Bakery Chat](https://github.com/SaimKhalid388/BAKERY-CHAT) &nbsp;·&nbsp; Domain RAG Chatbot

Not a ChatGPT wrapper. A properly engineered retrieval pipeline built for a real business domain.

**Workflow:** User query → dual retrieval fires (FAISS vector similarity + Whoosh full-text keyword search) → results reranked → prompt assembled with context → Groq LLM generates → response postprocessed → session memory updated.

> **The engineering challenge:** Hybrid retrieval (vector + keyword combined) consistently outperforms either engine alone. True multi-turn session memory — the bot remembers the full conversation, not just the last message. Every pipeline step is explicitly engineered, not assumed by the model.

```
Stack: Python · FastAPI · FAISS · Whoosh · Groq API · Pydantic · Uvicorn · React
```

---

## Tech Stack

**AI & Language Models**

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=58A6FF)
![OpenAI](https://img.shields.io/badge/OpenAI-0d1117?style=flat-square&logo=openai&logoColor=58A6FF)
![LangChain](https://img.shields.io/badge/LangChain-0d1117?style=flat-square&logo=langchain&logoColor=58A6FF)
![HuggingFace](https://img.shields.io/badge/HuggingFace-0d1117?style=flat-square&logo=huggingface&logoColor=58A6FF)
![Groq](https://img.shields.io/badge/Groq-0d1117?style=flat-square&logo=data:image/svg+xml;base64,PHN2Zy8+&logoColor=58A6FF)

**Vector Search & RAG**

![FAISS](https://img.shields.io/badge/FAISS-0d1117?style=flat-square&logo=meta&logoColor=58A6FF)
![ChromaDB](https://img.shields.io/badge/ChromaDB-0d1117?style=flat-square&logoColor=58A6FF)
![Pinecone](https://img.shields.io/badge/Pinecone-0d1117?style=flat-square&logoColor=58A6FF)
![Whoosh](https://img.shields.io/badge/Whoosh_Full--Text-0d1117?style=flat-square&logoColor=58A6FF)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=flat-square&logo=fastapi&logoColor=58A6FF)
![Pydantic](https://img.shields.io/badge/Pydantic-0d1117?style=flat-square&logo=pydantic&logoColor=58A6FF)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=58A6FF)
![SQLite](https://img.shields.io/badge/SQLite-0d1117?style=flat-square&logo=sqlite&logoColor=58A6FF)

**Frontend**

![React](https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=58A6FF)
![Vite](https://img.shields.io/badge/Vite-0d1117?style=flat-square&logo=vite&logoColor=58A6FF)
![TailwindCSS](https://img.shields.io/badge/Tailwind-0d1117?style=flat-square&logo=tailwindcss&logoColor=58A6FF)
![Streamlit](https://img.shields.io/badge/Streamlit-0d1117?style=flat-square&logo=streamlit&logoColor=58A6FF)

**Optimization & Maps**

![OSRM](https://img.shields.io/badge/OSRM_Routing-0d1117?style=flat-square&logoColor=58A6FF)
![Folium](https://img.shields.io/badge/Folium-0d1117?style=flat-square&logo=leaflet&logoColor=58A6FF)
![GA](https://img.shields.io/badge/Genetic_Algorithm-0d1117?style=flat-square&logoColor=58A6FF)

---

## GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=SaimKhalid388&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=58A6FF&text_color=c9d1d9&icon_color=1f6feb&rank_icon=github"/>
&nbsp;
<img height="170" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=SaimKhalid388&theme=github_dark&layout=compact&hide_border=true&bg_color=0d1117&title_color=58A6FF&text_color=c9d1d9&langs_count=8"/>

</div>

<div align="center">

<img width="70%" src="https://github-readme-streak-stats.herokuapp.com/?user=SaimKhalid388&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=21262d&ring=1f6feb&fire=58A6FF&currStreakLabel=c9d1d9&sideLabels=c9d1d9&dates=8b949e&currStreakNum=e6edf3&sideNums=e6edf3"/>

</div>

<div align="center">

<img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=SaimKhalid388&theme=github-compact&hide_border=true&bg_color=0d1117&color=58A6FF&line=1f6feb&point=58A6FF&area=true&area_color=1f6feb"/>

</div>

<div align="center">

<img width="96%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=SaimKhalid388&theme=github_dark"/>

</div>

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=SaimKhalid388&theme=github_dark&no-frame=true&no-bg=true&column=7&margin-w=6"/>

</div>

---

## Let's Talk

I'm actively looking for **AI Engineer · LLM Developer · ML Engineer** roles — remote or Pakistan-based.

If you're building in the AI space and want someone who ships full-stack AI products — frontend, backend, and the AI layer — reach out.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-1f6feb?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saimkhalid/)
&nbsp;
[![Email](https://img.shields.io/badge/saim.khalid983%40gmail.com-1f6feb?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saim.khalid983@gmail.com)

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:0d1117&height=100&section=footer&animation=fadeIn" width="100%"/>
</div>
