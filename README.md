<!-- github.com/Davan57/Davan57 -->
<!-- Profile README drives the entire landing page of your GitHub profile -->

<h1 align="center">Hi, I'm Davan C Reddy 👋</h1>
<p align="center">
  AI/ML • RAG/GraphRAG • Full-stack • DevOps<br/>
  B.E. CSD @ Dayananda Sagar (CGPA 9.22)
</p>

<p align="center">
  <a href="mailto:davanc2004@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-davanc2004%40gmail.com-red"></a>
  <a href="https://www.linkedin.com/in/davan-c-reddy/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2"></a>
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=Davan57&label=Profile%20views&color=0e75b6&style=flat" />
</p>

---

## 🚀 I build
- **GraphRAG Knowledge Retrieval** — hybrid vector + knowledge-graph strategies with local/global retrieval.
- **Realtime AI Collaboration** — session-aware LLM chat + Monaco editor sync (Socket.io, KeyDB).
- **ML Security** — Network Intrusion Detection with stream-ready inference.
- **Vision & Analytics** — Waste classifier app • TTS summarization • Power BI dashboards.

---

## 🧭 Spotlight (quick hop)
- 🔎 **RAG / GraphRAG** — retrieval pipelines, evaluation harnesses, and tracing.  
- ⚡ **Realtime** — low-latency collaboration primitives for editors, slides, and media.  
- 🔐 **Security** — anomaly/attack detection and robust feature engineering.  
- 🧰 **Tooling** — clean repos, CI, Docker, reproducible envs.

---

## 🛠️ Toolbox
**Languages**: Python, Java, JS/TS, SQL, C, ABAP  
**ML/AI**: TensorFlow, scikit-learn, LangChain, RAG, Graph databases  
**Cloud/DevOps**: Docker, GitHub Actions, Linux, Azure, Power BI, BigQuery, ServiceNow

---

## 🧩 System sketches (Mermaid)
```mermaid
flowchart LR
  U[User] -->|Query| Q(Orchestrator)
  subgraph Retrieval
    V[Vector Index] --- G[Knowledge Graph]
  end
  Q --> V
  Q --> G
  V --> C[Context Builder]
  G --> C
  C --> L[LLM]
  L --> A[Answer + Traces]
mermaid
sequenceDiagram
  participant Client
  participant Gateway
  participant Collab(Realtime Service)
  participant LLM
  Client->>Gateway: Auth + Init
  Gateway->>Collab: Join room (KeyDB)
  Client->>Collab: Edit events (Monaco)
  Collab-->>Client: Broadcast diffs
  Client->>LLM: Contextual prompt
  LLM-->>Client: Response
```

## 📈 Activity & stats
<p align="center"> <!-- GitHub Readme Stats (lightweight, no token required) --> <img src="https://github-readme-stats.vercel.app/api?username=Davan57&show_icons=true&hide_rank=false" height="165" /> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Davan57&layout=compact" height="165" /> </p>

---

## 🎓 Certifications
ServiceNow CSA & CAD • Google Data Analytics • ML Specialization (Stanford/DeepLearning.AI)

---

## 📬 Reach me
Email: davanc2004@gmail.com

LinkedIn: linkedin.com/in/davan-c-reddy



