
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:8b5cf6,100:a855f7&height=220&section=header&text=Hey%2C%20I%27m%20Saim%20%F0%9F%91%8B&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=I%20build%20AI%20systems%20that%20actually%20ship&descSize=20&descAlignY=62&descColor=e2e8f0" />

</div>

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=18&duration=2800&pause=800&color=A78BFA&center=true&vCenter=true&width=700&lines=AI+Engineer+from+Pakistan+%F0%9F%87%B5%F0%9F%87%B0+%E2%80%94+Open+to+Remote+Worldwide;I+turn+messy+PDFs+into+queryable+intelligence;I+route+vehicles+on+real+roads+with+Genetic+Algorithms;I+ship+React+%2B+FastAPI+%2B+LLMs+as+one+product;Not+a+researcher.+An+engineer+who+delivers." />

</div>

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saimkhalid/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saim.khalid983@gmail.com)
[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/saimcodes)
[![Profile Views](https://komarev.com/ghpvc/?username=SaimKhalid388&label=Profile+Views&color=6366f1&style=for-the-badge)](https://github.com/SaimKhalid388)

</div>

---

## 🧠 About Me

I'm an **AI Engineer** who builds *complete* AI products — not Colab notebooks, not proof-of-concepts. I care about the full stack: the LLM layer, the retrieval pipeline, the API, and the UI that a real human sits in front of.

My three shipped projects span **enterprise procurement automation**, **logistics optimization**, and **conversational AI** — three different industries, three real use cases, three working full-stack applications.

**What drives me:** Every problem I've solved started with a person wasting hours on something a well-built AI system could handle in seconds. I build those systems.

```
🔭 Currently working on  →  LLM apps for enterprise automation
🌱 Deepening expertise in  →  multi-agent orchestration & fine-tuning
💬 Ask me about  →  RAG pipelines, FastAPI, OpenAI APIs, system design
📍 Based in  →  Pakistan · Available remotely worldwide
💼 Status  →  Actively looking for AI / LLM / ML Engineer roles
📧 Reach me at  →  saim.khalid983@gmail.com
```

---

## 🚀 What I've Built

> Three production-ready AI applications. Real repos. Real code. Click and explore.

<br/>

<table width="100%">
<tr>

<td width="34%" valign="top" style="padding: 12px;">

### 📄 Smart RFP System
> *AI that reads vendor proposals so humans don't have to*

Procurement teams manually copy vendor data from PDFs into spreadsheets for hours. This system eliminates that entirely.

**Upload RFP → AI extracts structure → vendors submit proposals → AI parses, compares, and scores everything → radar charts + ranked shortlist.**

You can also *chat* with any proposal: *"Which vendor offers the longest warranty?"*

**Stack**
`GPT-4o` · `ChromaDB` · `text-embedding-3-large` · `FastAPI` · `React + Vite` · `TailwindCSS` · `ApexCharts` · `SQLite`

**Why it's non-trivial**
Structured extraction from unstructured PDFs at scale, 3072-dim embeddings for semantic search, vendor data aligned column-by-column for fair comparison, with Groq as a live fallback if OpenAI goes down.

<div align="center">

[![View Repo →](https://img.shields.io/badge/View%20Repo%20%E2%86%92-6366f1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SaimKhalid388/smart-rfp-system)

</div>

</td>

<td width="33%" valign="top" style="padding: 12px;">

### 🚌 VRP — Route Optimizer
> *Genetic algorithms. Real roads. Real fleet constraints.*

Companies running employee shuttle services route vehicles on gut feel. This system optimizes it mathematically.

**Multi-depot → factory routing, real shift times, mixed fleet (owned + rented), hard capacity limits — solved with a Genetic Algorithm that plans routes on actual road networks via OSRM, not straight lines.**

Results show up as an interactive Folium map with per-route breakdowns: passengers, cost, distance, time.

**Stack**
`Python` · `FastAPI` · `React` · `Genetic Algorithm` · `OSRM` · `Folium` · `Leaflet.js`

**Why it's non-trivial**
VRP is NP-hard. The GA uses a deterministic feasibility decoder with OSRM segment caching for performance. Dual interface: CLI for engineers, full web UI for operations teams.

<div align="center">

[![View Repo →](https://img.shields.io/badge/View%20Repo%20%E2%86%92-8b5cf6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SaimKhalid388/VRP)

</td>

<td width="33%" valign="top" style="padding: 12px;">

### 🥐 Bakery Chat
> *A RAG chatbot with two retrieval engines and memory*

Not a wrapper around ChatGPT. A proper Retrieval-Augmented Generation pipeline built for a real bakery business.

**User asks a question → dual retrieval fires (FAISS for vector similarity + Whoosh for keyword matching) → results are reranked → prompt is assembled → LLM generates → response is postprocessed → session memory updated.**

Every step is engineered, not assumed.

**Stack**
`Python` · `FastAPI` · `React` · `FAISS` · `Whoosh` · `Groq API` · `Pydantic` · `Uvicorn`

**Why it's non-trivial**
Hybrid retrieval (vector + keyword) consistently beats either alone. Multi-turn session management means the bot remembers context across messages, not just the last one.

<div align="center">

[![View Repo →](https://img.shields.io/badge/View%20Repo%20%E2%86%92-a855f7?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SaimKhalid388/BAKERY-CHAT)

</div>

</td>

</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

**AI & LLMs**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)

**Vector Search & RAG**

![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logoColor=white)
![Whoosh](https://img.shields.io/badge/Whoosh_Full--Text-4B5563?style=flat-square&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![Uvicorn](https://img.shields.io/badge/Uvicorn-4B8BBE?style=flat-square&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Geospatial & Optimization**

![OSRM](https://img.shields.io/badge/OSRM_Routing-6366f1?style=flat-square&logoColor=white)
![Folium](https://img.shields.io/badge/Folium-77B829?style=flat-square&logo=leaflet&logoColor=white)
![Genetic Algorithm](https://img.shields.io/badge/Genetic_Algorithm-0f766e?style=flat-square&logoColor=white)

**DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="175" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=SaimKhalid388&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=e2e8f0&icon_color=6366f1&rank_icon=github" />
&nbsp;
<img height="175" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=SaimKhalid388&theme=tokyonight&layout=compact&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=e2e8f0&langs_count=8" />

</div>

<div align="center">

<img width="70%" src="https://github-readme-streak-stats.herokuapp.com/?user=SaimKhalid388&theme=tokyonight&hide_border=true&background=0d1117&stroke=1e1b4b&ring=6366f1&fire=a78bfa&currStreakLabel=e2e8f0&sideLabels=e2e8f0&dates=64748b&currStreakNum=ffffff&sideNums=ffffff" />

</div>

<div align="center">

<img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=SaimKhalid388&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=a78bfa&line=6366f1&point=a78bfa&area=true&area_color=6366f1" />

</div>

<div align="center">

<img width="96%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=SaimKhalid388&theme=tokyonight" />

</div>

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=SaimKhalid388&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=6" />
</div>

---

## 💼 Why Hire Me

I don't just know the tools. I understand the problems they solve — and I've shipped products that prove it.

Every project above is a **full-stack AI application** with a real user problem behind it, a real technical challenge inside it, and real code you can read right now. That's the kind of engineer I am.

- ✅ I ship — React frontends, FastAPI backends, AI layers — together, as one product
- ✅ I think about production — fallbacks, caching, `.env` config, non-technical UIs
- ✅ I solve hard problems — NP-hard routing, structured PDF extraction, hybrid retrieval
- ✅ I adapt — procurement, logistics, retail — different domains, same engineering discipline

---

## 📬 Let's Connect

Open to **AI Engineer · LLM Developer · ML Engineer** roles — remote or Pakistan-based.

<div align="center">

[![LinkedIn — Let's connect](https://img.shields.io/badge/LinkedIn%20—%20Let's%20connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saimkhalid/)
[![Email — saim.khalid983@gmail.com](https://img.shields.io/badge/Email%20—%20saim.khalid983%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saim.khalid983@gmail.com)

</div>

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:a855f7,50:8b5cf6,100:6366f1&height=120&section=footer&fontColor=ffffff" />

</div>
