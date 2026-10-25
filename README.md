
```markdown
<div align="center">

  <!-- ANIMATED HERO BANNER -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,19,24&height=230&section=header&text=Adarsh%20Dubey&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%20%26%20ML%20Engineer%20%7C%20Multi-Agent%20Systems%20Architect%20%7C%20Full-Stack%20AI%20Builder&descAlignY=58&descSize=18" width="100%" alt="Adarsh Dubey Banner" />

  <!-- ANIMATED TYPING SVG -->
  <a href="https://github.com/adarsh-dubey-gthb">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=900&color=7AA2F7&center=true&vCenter=true&multiline=false&width=850&lines=Designing%2C+Building+%26+Deploying+Production+LLM+Applications+%F0%9F%A4%96;Automating+2%2C000%2B+Monthly+Bookings+via+Multi-Agent+Pipelines+%E2%9A%A1;LangGraph+%7C+CrewAI+%7C+FastAPI+%7C+Gemini+2.5+Flash+%7C+PyTorch+%F0%9F%A7%A0;Codeforces+1455+%7C+CodeChef+1416+%7C+Top+5%25+Kaggle+Competitor+%F0%9F%8F%86" alt="Typing SVG" />
  </a>

  <br/><br/>

  <!-- CONTACT & LIVE PORTFOLIO BADGES -->
  <a href="https://axiomtech.live" target="_blank">
    <img src="https://img.shields.io/badge/Live_Platform-axiomtech.live-7aa2f7?style=for-the-badge&logo=vercel&logoColor=white&labelColor=1a1b27" alt="Axiomtech.live" />
  </a>
  <a href="https://www.linkedin.com/in/adarsh-dubey-a9b5bb322/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Adarsh_Dubey-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=1a1b27" alt="LinkedIn" />
  </a>
  <a href="mailto:contact.adarshdubey@gmail.com">
    <img src="https://img.shields.io/badge/Email-contact.adarshdubey%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1a1b27" alt="Email" />
  </a>
  <img src="https://img.shields.io/badge/Location-Delhi_NCR,_India-bb9af7?style=for-the-badge&logo=googlemaps&logoColor=white&labelColor=1a1b27" alt="Location" />
  <img src="https://komarev.com/ghpvc/?username=adarsh-dubey-gthb&label=Profile%20Views&color=7dcfff&style=for-the-badge&labelColor=1a1b27" alt="Profile Views" />

</div>

<br/>

---

### ⚡ `whoami` — System Telemetry & Engineering Summary

```yaml
adarsh@ai-engine:~$ cat profile_manifest.yaml
──────────────────────────────────────────────────────────────────────────────────────────
👤 Engineer       : Adarsh Dubey (Delhi NCR, India)
🎯 Core Mission   : AI Engineer who designs, builds & deploys LLM apps, ML models & full-stack AI products
🎓 Education      : B.Tech in CSE @ ABES Engineering College, Ghaziabad (2024–2028) | SGPA: 8.0/10
💼 Current Role   : Founder & AI Engineer (Jan 2025 – Present) | Production B2B Multi-Agent Systems
🧠 Specializations: Multi-Agent Orchestration (LangGraph/CrewAI), Voice/Speech Pipelines, Predictive ML
🛡️ Engineering Law: Deterministic Python & Pydantic Schema Validation > Raw Unchecked LLM Reasoning
📈 Impact Metrics : 2,000+ Monthly Bookings Automated | 80% Faster Response | 500+ Dev Users on Axiom
⚔️ Algorithmic CP : Codeforces (Max 1455) | CodeChef (Max 1416) | LeetCode (126+ Solved) | Kaggle Top 5%

```

---

### 🏗️ Production AI & System Architectures

*Click the interactive toggles below to inspect the live engineering architectures behind my production deployments.*

> **Production Impact (Jan 2025 – Present):** Automated **2,000+ monthly bookings**, reduced manual response latency by **80%**, and saved **~15 admin hours/week** across two corporate transport companies (MST and Amigotours). Engineered with deterministic Python cross-checks and label-based idempotency to prevent duplicate writes during API rate-limit failures.

```mermaid
flowchart LR
    subgraph Ingestion["📥 1. Async Ingestion Layer"]
        A1["📧 Corporate Booking Emails<br/>(MST & Amigotours)"]
        A2["⚡ Asynchronous Webhooks<br/>& Event Listeners"]
    end

    subgraph AgentCore["🧠 2. Multi-Agent & Deterministic Validation"]
        B1["🤖 LLM Extraction &<br/>Tool-Calling Node"]
        B2["📐 Pydantic Schema<br/>Constrained Output"]
        B3["🐍 Deterministic Python<br/>High-Stakes Field Validator"]
        B1 --> B2 --> B3
    end

    subgraph Idempotency["🛡️ 3. Fault-Tolerant Persistence"]
        C1["🔍 Match-Before-Write<br/>Deduplication Engine"]
        C2["🏷️ Label-Based Idempotency<br/>(Rate-Limit Safe)"]
        C1 --> C2
    end

    subgraph Sinks["🚀 4. Production Sinks & Analytics"]
        D1[("🗄️ Production DB &<br/>Google Sheets Sync")]
        D2["📊 Automated REST API<br/>Analytics Reports (-15h/wk)"]
    end

    A1 & A2 --> B1
    B3 --> C1
    C2 --> D1 & D2

    style Ingestion fill:#1a1b27,stroke:#7aa2f7,stroke-width:2px,color:#fff
    style AgentCore fill:#16161e,stroke:#bb9af7,stroke-width:2px,color:#fff
    style Idempotency fill:#1a1b27,stroke:#e0af68,stroke-width:2px,color:#fff
    style Sinks fill:#1a1b27,stroke:#9ece6a,stroke-width:2px,color:#fff

```

> **Architecture Overview:** Full-stack real-time voice interviewer powered by **FastAPI, React, Gemini 2.5 Flash, and SQLite (WAL mode)**. Converts raw job descriptions and candidate resumes into a 3-level adaptive technical interview with live counter-questioning and diagnostic scoring.

```mermaid
flowchart TD
    subgraph Client["🖥️ React Frontend (BYOK Support)"]
        U1["📄 Resume + Job Description Upload"]
        U2["🎙️ Real-Time Speech-to-Text<br/>& Spoken Audio Stream"]
    end

    subgraph Backend["⚡ FastAPI + Gemini 2.5 Flash Engine"]
        E1["🧬 Context Parser &<br/>Rubric Generator"]
        E2["🔄 3-Level Adaptive<br/>Questioning Engine"]
        E3["🎯 Counter-Question &<br/>Diagnostic Scoring Node"]
        E1 --> E2 --> E3
    end

    subgraph Storage["🗄️ Concurrent Persistence Layer"]
        S1[("💾 SQLite (WAL Mode)<br/>via SQLAlchemy ORM")]
        S2["📑 Comprehensive Diagnostic<br/>Session Report"]
    end

    U1 --> E1
    U2 <--> E2
    E3 --> S1 --> S2

    style Client fill:#1a1b27,stroke:#7dcfff,stroke-width:2px,color:#fff
    style Backend fill:#16161e,stroke:#7aa2f7,stroke-width:2px,color:#fff
    style Storage fill:#1a1b27,stroke:#bb9af7,stroke-width:2px,color:#fff

```

> **Architecture Overview:** Autonomous **LangGraph + Gemini 2.5 Flash** ReAct research agent that dynamically plans web searches, scrapes articles/tables, enforces strict **Pydantic** validation, and renders live traces and **Plotly** radar charts inside **Streamlit**.

```mermaid
flowchart LR
    A["🎯 Target Company Query"] --> B["🕸️ LangGraph ReAct Planner"]
    B --> C["🌐 Autonomous Web Search<br/>& Table/Article Scraper"]
    C --> D["🛡️ Pydantic Type-Safe Validator<br/>(SWOT, Financials, Risks, Citations)"]
    D --> E1["📈 Streamlit Live Trace UI<br/>+ Plotly Radar Charts"]
    D --> E2["💬 Grounded Report Chatbot"]
    D --> E3["📦 Export Engine<br/>(Markdown / HTML / JSON)"]

    style A fill:#1a1b27,stroke:#7aa2f7,color:#fff
    style B fill:#16161e,stroke:#bb9af7,color:#fff
    style C fill:#1a1b27,stroke:#7dcfff,color:#fff
    style D fill:#16161e,stroke:#e0af68,color:#fff
    style E1 fill:#1a1b27,stroke:#9ece6a,color:#fff
    style E2 fill:#1a1b27,stroke:#9ece6a,color:#fff
    style E3 fill:#1a1b27,stroke:#9ece6a,color:#fff

```

---

### 🛠️ Categorized Technical Arsenal

| Domain | Technologies, Frameworks & Libraries |
| --- | --- |
| **Languages** |       |
| **AI, Agents & ML** |          |
| **Backend & Data** |          |
| **Frontend, Voice & Cloud** |       |
| **Vector DBs & DevOps** |       |

---

### 🚀 Featured Engineering Projects (6 Production & ML Builds)

---

### 🏆 Hackathons, Competitive Programming & Academic Pedigree

* 🏆 **Best Performing Team (Idea Pitching) — IDE Bootcamp Phase 2 (Apr 2026):** Awarded by the **Ministry of Education, AICTE, and Wadhwani Foundation**.
* 🇮🇳 **National Hackathon Finalist & Builder:**
* **Smart India Hackathon (SIH)**
* **AI4Bharat Hackathon**
* **Agentic AI Hackathon** (GL Bajaj)
* **Makeathon 8** (TIET Patiala)


* 🧠 **TATA Crucible Campus Quiz (2025):** National corporate & technology quiz competitor.

| Platform | Peak Rating / Milestone | Core Focus |
| --- | --- | --- |
|  | **Max Rating: 1455** | Algorithmic Problem Solving, Graphs, Greedy, DP (`C++`) |
|  | **Max Rating: 1416** | Timed Rated Contests & Number Theory (`C++`) |
|  | **126+ Solved** | Data Structures, Trees, Sliding Window, System Design |
|  | **Top 5% Rank** | Tabular ML, Feature Engineering & Hyperparameter Tuning |

* **Institution:** ABES Engineering College, Ghaziabad — *B.Tech in Computer Science and Engineering (Aug 2024 – May 2028)*
* **Academic Standing:** **SGPA: 8.0 / 10.0**
* **Core CS Coursework:** Data Structures & Algorithms (DSA), Object-Oriented Programming (OOP), Database Management Systems (DBMS), Operating Systems (OS), Computer Networks (CN), Machine Learning (ML).

---

### 📊 Live GitHub Telemetry & Contribution Velocity









---

### 🤝 Open to AI/ML Engineering Roles & High-Impact Collaborations

*Designing deterministic, production-grade multi-agent systems and full-stack AI applications.*

Would you like me to plug in the exact GitHub repository URLs for **Interview Accelerator**, **Market Intelligence Agent**, **Scholarship Intelligence Crawler**, **Project Yatra**, and **Employee Burnout Prediction** so the project cards have clickable `[Live Demo]` and `[GitHub Repo]` buttons?
