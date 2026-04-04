<!-- Header Banner -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1f6feb&height=140&section=header&text=&animation=fadeIn" width="100%"/>
</div>

<!-- Name + Animated Title -->
<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Syne&weight=800&size=42&duration=1&pause=99999&color=E6EDF3&center=true&vCenter=true&width=700&height=80&lines=Muhammad+Saim+Khalid" alt="Name"/>
  <br/>
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=17&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&height=40&lines=AI+Engineer+%7C+LLM+Systems+%7C+Full-Stack+AI+Apps;Building+AI+that+solves+real+business+problems;RAG+%C2%B7+Agents+%C2%B7+Optimization+%C2%B7+FastAPI+%C2%B7+React" alt="Role"/>
</div>

<br/>

<!-- Social Links -->
<div align="center">
  <a href="https://www.linkedin.com/in/saimkhalid/">
    <img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=58A6FF&labelColor=0d1117"/>
  </a>
  &nbsp;
  <a href="mailto:saim.khalid983@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-0d1117?style=for-the-badge&logo=gmail&logoColor=58A6FF&labelColor=0d1117"/>
  </a>
  &nbsp;
  <a href="https://twitter.com/saimcodes">
    <img src="https://img.shields.io/badge/Twitter-0d1117?style=for-the-badge&logo=x&logoColor=58A6FF&labelColor=0d1117"/>
  </a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=SaimKhalid388&style=for-the-badge&color=1f6feb&label=PROFILE+VIEWS&labelColor=0d1117"/>
</div>

<br/>

---

## &nbsp; Who I Am

I'm an **AI Engineer** from Pakistan 🇵🇰 who builds **complete, production-ready AI systems** — not prototypes, not notebooks. I care about the full picture: the retrieval pipeline, the API design, and the UI that a real person actually uses.

My three shipped projects span **enterprise procurement**, **logistics optimization**, and **domain-specific conversational AI** — three industries, three hard problems, three working full-stack applications you can open right now.

<table>
<tr>
<td>🔭 &nbsp;<b>Currently building</b></td>
<td>LLM-powered automation for enterprise workflows</td>
</tr>
<tr>
<td>🧠 &nbsp;<b>Deepening skills in</b></td>
<td>Multi-agent systems, LLM fine-tuning, production RAG at scale</td>
</tr>
<tr>
<td>📍 &nbsp;<b>Location</b></td>
<td>Pakistan — open to remote roles worldwide</td>
</tr>
<tr>
<td>💼 &nbsp;<b>Status</b></td>
<td><b>Actively looking</b> for AI / LLM / ML Engineer roles</td>
</tr>
<tr>
<td>📬 &nbsp;<b>Contact</b></td>
<td><a href="mailto:saim.khalid983@gmail.com">saim.khalid983@gmail.com</a></td>
</tr>
</table>

---

## &nbsp; Featured Projects

> Every project below is a real full-stack AI application. Click the links. The code is there.

<br/>

### &nbsp;📄 &nbsp;[Smart RFP System](https://github.com/SaimKhalid388/smart-rfp-system) &nbsp;—&nbsp; AI-Powered Procurement Platform

> *Procurement teams spend hours copying vendor proposal data into spreadsheets. This system eliminates that entirely.*

**The workflow:** Upload an RFP PDF → AI extracts requirements and form structure → vendors submit proposals → AI parses pricing, timelines, materials, warranties → side-by-side comparison matrix → radar charts + AI-scored vendor ranking. You can also **chat** with any proposal in natural language.

**What makes it hard:** Structured extraction from unstructured PDFs at scale. Vendor data aligned column-by-column for fair apples-to-apples comparison. 3072-dim embeddings in ChromaDB for semantic proposal search. Live Groq fallback if OpenAI goes down — it keeps working.

<div align="center">

| Layer | Technology |
|---|---|
| **AI** | GPT-4o · text-embedding-3-large · Groq (fallback) |
| **Backend** | Python · FastAPI · SQLite · ChromaDB |
| **Frontend** | React · Vite · TailwindCSS · ApexCharts |

</div>

[![View Repo](https://img.shields.io/badge/View%20Repo%20→-1f6feb?style=flat-square&logo=github&logoColor=white)](https://github.com/SaimKhalid388/smart-rfp-system)

---

### &nbsp;🚌 &nbsp;[VRP Optimizer](https://github.com/SaimKhalid388/VRP) &nbsp;—&nbsp; Multi-Depot Employee Transport Solver

> *Fleet managers routing employee shuttles on gut feel instead of math. This changes that.*

**The workflow:** Define depots, factory, shifts, and fleet → Genetic Algorithm solves the routing problem → routes computed on **actual roads** via OSRM (not straight lines) → interactive Folium map with per-route breakdown: passengers, cost, time, distance.

**What makes it hard:** VRP is NP-hard. The GA uses a deterministic feasibility decoder that respects owned vehicle counts, rented vehicle fixed costs, shift timing, and seat capacity — all simultaneously. OSRM segment caching prevents redundant road API calls. Dual interface: CLI for engineers, full web app for operations teams who don't touch a terminal.

<div align="center">

| Layer | Technology |
|---|---|
| **Solver** | Python · Genetic Algorithm · Deterministic Feasibility Decoder |
| **Routing** | OSRM (real-road distances + times) · Segment caching |
| **Interface** | FastAPI · React · Folium · Leaflet.js |

</div>

[![View Repo](https://img.shields.io/badge/View%20Repo%20→-1f6feb?style=flat-square&logo=github&logoColor=white)](https://github.com/SaimKhalid388/VRP)

---

### &nbsp;🥐 &nbsp;[Bakery Chat](https://github.com/SaimKhalid388/BAKERY-CHAT) &nbsp;—&nbsp; Domain-Specific RAG Chatbot

> *Not a ChatGPT wrapper. A properly engineered retrieval pipeline built for a real business domain.*

**The workflow:** User asks a question → **dual retrieval** fires in parallel (FAISS vector similarity + Whoosh full-text keyword search) → results reranked → prompt assembled with context → Groq LLM generates → response postprocessed → session memory updated.

**What makes it hard:** Hybrid retrieval (vector + keyword combined) consistently outperforms either engine alone. True multi-turn session memory — the bot remembers the whole conversation, not just the last message. Every step is explicitly engineered, not assumed by the model.

<div align="center">

| Layer | Technology |
|---|---|
| **Retrieval** | FAISS (vector) + Whoosh (full-text) · Hybrid reranking |
| **Backend** | Python · FastAPI · Pydantic · Uvicorn · Groq API |
| **Frontend** | React · Session Management |

</div>

[![View Repo](https://img.shields.io/badge/View%20Repo%20→-1f6feb?style=flat-square&logo=github&logoColor=white)](https://github.com/SaimKhalid388/BAKERY-CHAT)

---

## &nbsp; Tech Stack

<div align="center">

**AI & Language Models**

<img src="https://skillicons.dev/icons?i=python,pytorch&theme=dark" />
&nbsp;
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white"/>

**Vector Search & RAG**

<img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white"/>
<img src="https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/Whoosh_Full--Text-374151?style=flat-square&logoColor=white"/>

**Backend & APIs**

<img src="https://skillicons.dev/icons?i=fastapi,docker,git&theme=dark" />
&nbsp;
<img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white"/>
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white"/>

**Frontend**

<img src="https://skillicons.dev/icons?i=react,vite,tailwind&theme=dark" />
&nbsp;
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>

**Geospatial & Optimization**

<img src="https://img.shields.io/badge/OSRM_Real--Road_Routing-1f6feb?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/Folium_Maps-77B829?style=flat-square&logo=leaflet&logoColor=white"/>
<img src="https://img.shields.io/badge/Genetic_Algorithm-0f766e?style=flat-square&logoColor=white"/>

</div>

---

## &nbsp; GitHub Stats

<div align="center">
  <img height="180" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=SaimKhalid388&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=58A6FF&text_color=c9d1d9&icon_color=1f6feb&rank_icon=github"/>
  &nbsp;
  <img height="180" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=SaimKhalid388&theme=github_dark&layout=compact&hide_border=true&bg_color=0d1117&title_color=58A6FF&text_color=c9d1d9&langs_count=8"/>
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

## &nbsp; Let's Talk

I'm actively looking for **AI Engineer · LLM Developer · ML Engineer** roles — remote or Pakistan-based.

If you're building in the AI space and want someone who ships **full-stack AI products** — frontend, backend, and everything in between — reach out.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=58A6FF&labelColor=0d1117)](https://www.linkedin.com/in/saimkhalid/)
&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/saim.khalid983%40gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=58A6FF&labelColor=0d1117)](mailto:saim.khalid983@gmail.com)

</div>

<br/>

<!-- Footer -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:0d1117&height=100&section=footer&text=&animation=fadeIn" width="100%"/>
</div>
