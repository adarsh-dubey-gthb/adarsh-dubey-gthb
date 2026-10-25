<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=gradient&amp;customColorList=12,14,19,24&amp;height=220&amp;section=header&amp;text=Adarsh%20Dubey&amp;fontSize=60&amp;fontColor=ffffff&amp;animation=fadeIn&amp;fontAlignY=35&amp;desc=Founder%20%40%20Axiom%20%7C%20AI%20Agent%20Architect%20%40%20CrewBot%20%7C%20Full-Stack%20Engineer&amp;descAlignY=58&amp;descSize=18" width="100%" alt="Adarsh Dubey: Founder at Axiom, AI Agent Architect at CrewBot, Full-Stack Engineer">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=22&amp;duration=3000&amp;pause=1000&amp;color=7AA2F7&amp;center=true&amp;vCenter=true&amp;multiline=false&amp;width=750&amp;lines=Building+B2B+SaaS+%40+axiomtech.live+%F0%9F%9A%80;Orchestrating+Multi-Agent+Workflows+%40+CrewBot+AI+%F0%9F%A4%96;C%2B%2B+Competitive+Programmer+%26+Full-Stack+Developer+%F0%9F%92%BB;Night+Owl+Coder+%F0%9F%A6%89+%7C+Evening+Gym+Rat+%F0%9F%8F%8B%EF%B8%8F%E2%80%8D%E2%99%82%EF%B8%8F+%7C+Cinematic+Creator+%F0%9F%8E%AC" alt="Animated headline: Building B2B SaaS at axiomtech.live, orchestrating multi-agent workflows at CrewBot AI, C++ competitive programmer and full-stack developer, night owl coder and cinematic creator">

<br>

<a href="https://axiomtech.live"><img src="https://img.shields.io/badge/Website-axiomtech.live-7aa2f7?style=for-the-badge&amp;logo=safari&amp;logoColor=7aa2f7&amp;labelColor=1a1b27" alt="Visit axiomtech.live"></a>
<a href="https://www.linkedin.com/in/adarsh-dubey-a9b5bb322/"><img src="https://img.shields.io/badge/LinkedIn-Connect-bb9af7?style=for-the-badge&amp;logo=linkedin&amp;logoColor=bb9af7&amp;labelColor=1a1b27" alt="Connect with Adarsh Dubey on LinkedIn"></a>
<a href="mailto:adarsh@axiomtech.live"><img src="https://img.shields.io/badge/Gmail-adarsh%40axiomtech.live-7dcfff?style=for-the-badge&amp;logo=gmail&amp;logoColor=7dcfff&amp;labelColor=1a1b27" alt="Email adarsh@axiomtech.live"></a>
<!-- Replace the URL below with your Instagram profile link -->
<a href="https://www.instagram.com/"><img src="https://img.shields.io/badge/Instagram-Cinematic_Reels-7aa2f7?style=for-the-badge&amp;logo=instagram&amp;logoColor=7aa2f7&amp;labelColor=1a1b27" alt="Adarsh Dubey on Instagram"></a>

<sub>Also reachable at <a href="mailto:contact.adarshdubey@gmail.com">contact.adarshdubey@gmail.com</a> · <a href="https://www.linkedin.com/in/adarshdubeydl/">alternate LinkedIn profile</a></sub>

</div>

<br>

### About Me

```yaml
# adarsh_os.sh : system fetch
user: adarsh@axiom
os: "Night Owl Developer"
host: "ABES Engineering College, Ghaziabad"
education: "B.Tech, Computer Science & Engineering (Class of 2028)"
status: "Building Axiom, running CrewBot AI"
roles:
  - "Founder & Lead Developer @ Axiom (axiomtech.live)"
  - "Founder & Lead AI Architect @ CrewBot AI"
  - "Previously: AI Agent Development Intern @ Gravity AI"
architecture_focus:
  - "Multi-agent workflows (CrewAI, Gemini)"
  - "Webhook-driven automation and Google Sheets pipelines"
  - "B2B SaaS: Django / Node.js backends, React dashboards, browser extensions"
agency_work: "Corporate transport automation for MST Mobility and Amigotours"
competitive_shell: "C++ (STL)"
off_screen:
  - "Evening gym"
  - "Cinematic developer storytelling on Instagram"
uptime: "Late nights"
```

### System Architecture

<details open>
<summary><b>CrewBot AI: Multi-Agent Production Pipeline</b></summary>
<br>

```mermaid
flowchart LR
    subgraph T["Incoming Triggers"]
        E1["Client Emails<br/>MST Mobility / Amigotours"]
        W1["Meta WhatsApp Webhooks"]
    end

    subgraph I["Ingestion Layer"]
        L["Python / FastAPI / Django<br/>Webhook Listener"]
    end

    subgraph C["CrewAI Orchestrator"]
        P["Parser Agent"]
        G["Gemini LLM<br/>Reasoning Node"]
        V["Validation Agent"]
    end

    subgraph A["Automated Action Layer"]
        S["Google Sheets API<br/>Real-time Sync"]
        D["Automated Dispatch<br/>Confirmation"]
        X["Exception Alerting"]
    end

    E1 --> L
    W1 --> L
    L --> P
    P --> G
    G --> V
    V -->|valid| S
    V -->|valid| D
    V -.->|ambiguous or failed| X

    classDef tokyo fill:#1a1b27,stroke:#7aa2f7,color:#fff,stroke-width:2px;
    classDef agent fill:#1a1b27,stroke:#bb9af7,color:#fff,stroke-width:2px;
    class E1,W1,L,S,D,X tokyo;
    class P,G,V agent;
    style T fill:#16161e,stroke:#414868,color:#7dcfff
    style I fill:#16161e,stroke:#414868,color:#7dcfff
    style C fill:#16161e,stroke:#414868,color:#7dcfff
    style A fill:#16161e,stroke:#414868,color:#7dcfff
    linkStyle default stroke:#7aa2f7,stroke-width:2px
```

</details>

<details>
<summary><b>Axiom (axiomtech.live): Ecosystem Architecture</b></summary>
<br>

```mermaid
flowchart LR
    subgraph SRC["Developer Sources"]
        GH["GitHub"]
        LC["LeetCode"]
        CF["Codeforces"]
        CC["CodeChef"]
        HR["HackerRank"]
    end

    EXT["Axiom Connector<br/>MS Edge Extension"]

    subgraph ENG["Aggregation Layer"]
        SC["Aggregation and<br/>Rate-Limited Scraping Engine"]
    end

    BE["Django / Node.js Backend"]

    subgraph UI["Product Surfaces"]
        FE["React Dashboard"]
        RA["Enterprise Recruiter<br/>Analytics View"]
    end

    GH --> SC
    LC --> SC
    CF --> SC
    CC --> SC
    HR --> SC
    EXT --> SC
    SC --> BE
    BE --> FE
    BE --> RA

    classDef tokyo fill:#1a1b27,stroke:#7aa2f7,color:#fff,stroke-width:2px;
    classDef accent fill:#1a1b27,stroke:#bb9af7,color:#fff,stroke-width:2px;
    class GH,LC,CF,CC,HR,SC,BE tokyo;
    class EXT,FE,RA accent;
    style SRC fill:#16161e,stroke:#414868,color:#7dcfff
    style ENG fill:#16161e,stroke:#414868,color:#7dcfff
    style UI fill:#16161e,stroke:#414868,color:#7dcfff
    linkStyle default stroke:#7aa2f7,stroke-width:2px
```

</details>

### Tech Arsenal

<div align="center">

<table>
  <tr>
    <td align="center"><b>Languages</b></td>
    <td align="left">
      <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&amp;logo=cplusplus&amp;logoColor=white" alt="C++">
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&amp;logo=typescript&amp;logoColor=white" alt="TypeScript">
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&amp;logo=javascript&amp;logoColor=black" alt="JavaScript">
      <img src="https://img.shields.io/badge/SQL-003B57?style=for-the-badge&amp;logo=sqlite&amp;logoColor=white" alt="SQL">
    </td>
  </tr>
  <tr>
    <td align="center"><b>AI &amp; Agentic Workflows</b></td>
    <td align="left">
      <img src="https://img.shields.io/badge/CrewAI-FF5A50?style=for-the-badge&amp;logo=crewai&amp;logoColor=white" alt="CrewAI">
      <img src="https://img.shields.io/badge/Google_Gemini_API-8E75B2?style=for-the-badge&amp;logo=googlegemini&amp;logoColor=white" alt="Google Gemini API">
      <img src="https://img.shields.io/badge/Faster--Whisper-1a1b27?style=for-the-badge&amp;labelColor=1a1b27&amp;color=7aa2f7" alt="Faster-Whisper">
      <img src="https://img.shields.io/badge/Indic_TTS-1a1b27?style=for-the-badge&amp;labelColor=1a1b27&amp;color=bb9af7" alt="Indic TTS">
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&amp;logo=langchain&amp;logoColor=white" alt="LangChain">
      <img src="https://img.shields.io/badge/Webhooks-1a1b27?style=for-the-badge&amp;labelColor=1a1b27&amp;color=7dcfff" alt="Webhooks">
    </td>
  </tr>
  <tr>
    <td align="center"><b>Backend &amp; Cloud</b></td>
    <td align="left">
      <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&amp;logo=django&amp;logoColor=white" alt="Django">
      <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&amp;logo=nodedotjs&amp;logoColor=white" alt="Node.js">
      <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&amp;logo=express&amp;logoColor=white" alt="Express">
      <img src="https://img.shields.io/badge/REST_APIs-85EA2D?style=for-the-badge&amp;logo=swagger&amp;logoColor=black" alt="REST APIs">
      <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&amp;logo=render&amp;logoColor=black" alt="Render">
      <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&amp;logo=linux&amp;logoColor=black" alt="Linux">
      <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&amp;logo=powershell&amp;logoColor=white" alt="PowerShell">
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&amp;logo=git&amp;logoColor=white" alt="Git">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white" alt="GitHub">
    </td>
  </tr>
  <tr>
    <td align="center"><b>Frontend &amp; Extensions</b></td>
    <td align="left">
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&amp;logo=react&amp;logoColor=61DAFB" alt="React.js">
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&amp;logo=html5&amp;logoColor=white" alt="HTML5">
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&amp;logo=css3&amp;logoColor=white" alt="CSS3">
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&amp;logo=tailwindcss&amp;logoColor=white" alt="Tailwind CSS">
      <img src="https://img.shields.io/badge/Edge_Extensions_API-0078D7?style=for-the-badge&amp;logo=microsoftedge&amp;logoColor=white" alt="Browser Extensions API for Microsoft Edge">
    </td>
  </tr>
</table>

</div>

### Featured Production Showcase

<div align="center">

<table>
  <tr>
    <td width="50%" valign="top" align="left">
      <b>Axiom</b> · <a href="https://axiomtech.live">axiomtech.live</a><br>
      <sub>B2B SaaS talent platform + Axiom Connector (MS Edge extension)</sub><br><br>
      Aggregates developer credentials and real-time portfolio metrics across GitHub, LeetCode, Codeforces, CodeChef, and HackerRank. Deployed on Render with a custom domain; the Axiom Connector extension is published on the Microsoft Edge Add-ons store.<br><br>
      <b>60+</b> concurrent users in live beta<br>
      <b>1st place</b>, IDE Bootcamp Edition 3 pitching competition<br><br>
      <sub><code>Django</code> · <code>Node.js</code> · <code>React</code> · <code>Edge Extension</code> · <code>Render</code></sub>
    </td>
    <td width="50%" valign="top" align="left">
      <b>CrewBot AI Automation Suite</b><br>
      <sub>Multi-agent booking and email-to-Sheets extraction</sub><br><br>
      Production multi-agent system for corporate transport clients (MST Mobility and Amigotours): booking management, Meta Webhook integrations, and automated extraction of email data into Google Sheets.<br><br>
      <a href="#system-architecture">See the pipeline diagram</a><br><br>
      <sub><code>Python</code> · <code>CrewAI</code> · <code>Gemini</code> · <code>Google Sheets API</code> · <code>Webhooks</code></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top" align="left">
      <b>NewsTTS</b><br>
      <sub>Real-time AI audio dubbing web application</sub><br><br>
      Dubs news content into audio using speech recognition and Indic text-to-speech models behind a Django web interface.<br><br>
      <sub><code>Django</code> · <code>Faster-Whisper</code> · <code>Indic TTS</code></sub><br><br>
      <a href="https://github.com/adarsh-dubey-gthb?tab=repositories">Browse my repositories</a>
    </td>
    <td width="50%" valign="top" align="left">
      <b>IntelliTransit, AI Interviewer &amp; Scholarship Scraper</b><br>
      <sub>Data, AI, and automation projects</sub><br><br>
      Published a GTFS public transportation dataset on Kaggle (Smart India Hackathon project), alongside an interactive Gemini-powered AI Interviewer platform and an automated scholarship scraper.<br><br>
      <sub><code>Python</code> · <code>Gemini API</code> · <code>GTFS</code> · <code>Web scraping</code></sub><br><br>
      <a href="https://github.com/adarsh-dubey-gthb?tab=repositories">Browse my repositories</a>
    </td>
  </tr>
</table>

</div>

### Milestones

<details>
<summary><b>🏆 Hackathons, Wins &amp; Recognition</b></summary>
<br>

- **Winner (1st Place):** Pitching Competition at Innovation, Design & Entrepreneurship (IDE) Bootcamp Edition 3, SGT University, for Axiom.
- **Competitor & Builder:** Smart India Hackathon (IntelliTransit) and AI for Bharat Hackathon.

</details>

<details>
<summary><b>⚔️ Competitive Programming &amp; Problem Solving</b></summary>
<br>

Primary language: **C++ (STL)**

<!-- Swap each "coming soon" badge for a live rating badge once you pick a rating source -->
| Platform | Profile | Language | Live rating |
| :--- | :--- | :--- | :--- |
| LeetCode | [adarshdubey_007](https://leetcode.com/u/adarshdubey_007/) | `C++ STL` | ![LeetCode rating slot](https://img.shields.io/badge/rating-coming_soon-565f89?style=flat-square&labelColor=1a1b27) |
| Codeforces | [adarshdubey_007](https://codeforces.com/profile/adarshdubey_007) | `C++ STL` | ![Codeforces rating slot](https://img.shields.io/badge/rating-coming_soon-565f89?style=flat-square&labelColor=1a1b27) |
| CodeChef | [contact_adarsh](https://www.codechef.com/users/contact_adarsh) | `C++ STL` | ![CodeChef rating slot](https://img.shields.io/badge/rating-coming_soon-565f89?style=flat-square&labelColor=1a1b27) |
| HackerRank | add handle | `C++ STL` | ![HackerRank rating slot](https://img.shields.io/badge/rating-coming_soon-565f89?style=flat-square&labelColor=1a1b27) |

</details>

<details>
<summary><b>🎬 Beyond the Terminal (Content &amp; Lifestyle)</b></summary>
<br>

- **Instagram creator journey:** cinematic developer storytelling, with voiceovers, aesthetic coding routines, and project-building reels.
- **Evening gym discipline:** a fixed evening session that balances late-night coding.
- **Night owl by default:** most shipping happens after dark.

</details>

### Live GitHub Analytics

<div align="center">

<table>
  <tr>
    <td align="center" valign="top">
      <img src="https://github-readme-stats.vercel.app/api?username=adarsh-dubey-gthb&amp;show_icons=true&amp;theme=tokyonight&amp;hide_border=true&amp;bg_color=1a1b27&amp;title_color=7aa2f7&amp;icon_color=bb9af7" alt="GitHub statistics for adarsh-dubey-gthb">
    </td>
    <td align="center" valign="top">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=adarsh-dubey-gthb&amp;layout=compact&amp;theme=tokyonight&amp;hide_border=true&amp;bg_color=1a1b27&amp;title_color=7aa2f7" alt="Most-used programming languages in public repositories of adarsh-dubey-gthb">
    </td>
  </tr>
</table>

<img src="https://streak-stats.demolab.com?user=adarsh-dubey-gthb&amp;theme=tokyonight&amp;hide_border=true&amp;background=1a1b27&amp;ring=7aa2f7&amp;fire=bb9af7&amp;currStreakLabel=7dcfff" alt="GitHub contribution streak for adarsh-dubey-gthb">

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=adarsh-dubey-gthb&amp;bg_color=1a1b27&amp;color=7aa2f7&amp;line=bb9af7&amp;point=7dcfff&amp;area=true&amp;hide_border=true" width="100%" alt="Contribution activity graph for adarsh-dubey-gthb">

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=gradient&amp;customColorList=12,14,19,24&amp;height=120&amp;section=footer" width="100%" alt="Decorative footer wave">

</div>
