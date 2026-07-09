<!--
  ┌─────────────────────────────────────────────────────────────────┐
  │          DIVYANSHU CHAUHAN — GitHub Profile README              │
  │     Repo: ChauhanDivyanshu/ChauhanDivyanshu  (README.md)       │
  │              Backend + AI Engineer · India 🇮🇳                  │
  └─────────────────────────────────────────────────────────────────┘
-->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F0C29,50:302B63,100:24243E&height=200&section=header&text=Divyanshu%20Chauhan&fontSize=50&fontColor=E2E8F0&animation=fadeIn&fontAlignY=38&desc=Backend%20Engineer%20·%20AI%20Systems%20·%20RAG%20in%20Production&descSize=16&descAlignY=58&descColor=94A3B8"/>

</div>

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&width=600&lines=Building+production+RAG+%2B+LLM+systems;Defence+sector+backend+%40+HAL+Korwa;50K%2B+users+protected+via+VerifyLayer+AI;FastAPI+%7C+LangChain+%7C+pgvector+%7C+Redis" alt="typing"/>

</div>

<br/>

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=googlechrome&logoColor=white)](https://divyanshu-chauhan-resume.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iamdivyanshuchauhan)
[![Linktree](https://img.shields.io/badge/Linktree-1A1A1A?style=for-the-badge&logo=linktree&logoColor=43E55E)](https://linktr.ee/Divyanshuchauhan10)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:divyanshuchauhan1200@gmail.com)
[![VerifyLayer AI](https://img.shields.io/badge/VerifyLayer_AI-8B5CF6?style=for-the-badge&logo=shield&logoColor=white)](https://verifylayer-ai.vercel.app/)

</div>

<br/>

---

## `$ whoami`

Hi 👋 I'm **Divyanshu**, a **Full Stack Python + AI Engineer** based in Noida, India.

I design and ship **production RAG systems, LLM-powered platforms, and backend architectures** — currently at **Infosware Private Limited**. My day-to-day involves solving problems where retrieval accuracy, latency, and cost all matter equally.

**🔨 What I'm building right now**
- 🤖 **White-Label RAG SaaS Platform** — Ollama · Llama 3.1 · pgvector · LangChain
- 🛡️ **SITS** — Defence inventory backend for **HAL Korwa Avionics**
- 🔍 **VerifyLayer AI** — India's AI scam-detection platform (50K+ users · 99.2% accuracy)

**🎯 What I care about**
- Retrieval quality **>** model size
- Async by default, sync only when forced
- Ship → measure → cut cost → repeat
- If it's not observable, it doesn't exist in production

**🌱 Currently learning**
- Agentic RAG · Multi-modal retrieval · eBPF observability

**💼 Open to**
- Backend roles · AI/ML engineering · Open-source collaboration

---

## `$ cat metrics.log`

<div align="center">

<table>
  <thead>
    <tr>
      <th align="left">Metric</th>
      <th align="center">Result</th>
      <th align="left">How</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>🎯 &nbsp; <b>Retrieval Accuracy</b></td>
      <td align="center"><img src="https://img.shields.io/badge/%2B40%25-6366F1?style=flat-square&labelColor=0F172A"/></td>
      <td>Multi-tier RAG pipeline</td>
    </tr>
    <tr>
      <td>⚡ &nbsp; <b>Processing Latency</b></td>
      <td align="center"><img src="https://img.shields.io/badge/%E2%88%9250%25-6366F1?style=flat-square&labelColor=0F172A"/></td>
      <td>Redis + Celery async</td>
    </tr>
    <tr>
      <td>💰 &nbsp; <b>AI Inference Cost</b></td>
      <td align="center"><img src="https://img.shields.io/badge/%E2%88%9225%25-6366F1?style=flat-square&labelColor=0F172A"/></td>
      <td>Prompt compression + cache</td>
    </tr>
    <tr>
      <td>🚫 &nbsp; <b>False Retrievals</b></td>
      <td align="center"><img src="https://img.shields.io/badge/%E2%88%9260%25-6366F1?style=flat-square&labelColor=0F172A"/></td>
      <td>Event-driven BM25 re-index</td>
    </tr>
    <tr>
      <td>🚀 &nbsp; <b>Deployment Time</b></td>
      <td align="center"><img src="https://img.shields.io/badge/30min%20%E2%86%92%205min-6366F1?style=flat-square&labelColor=0F172A"/></td>
      <td>Blue-green CI/CD</td>
    </tr>
    <tr>
      <td>📦 &nbsp; <b>QA Pipeline</b></td>
      <td align="center"><img src="https://img.shields.io/badge/3days%20%E2%86%92%202hrs-6366F1?style=flat-square&labelColor=0F172A"/></td>
      <td>NLP EPUB automation</td>
    </tr>
  </tbody>
</table>

</div>

---

## `$ ls -la projects/`

<details open>
<summary><b>🤖 &nbsp;White-Label RAG SaaS Platform</b> &nbsp;·&nbsp; <code>Production</code></summary>

<br/>

> Self-hosted · Multilingual · Cost-optimised RAG for Indian SMBs

```
                    RAG PIPELINE FLOW
    ─────────────────────────────────────────────

              User Query
                  │
                  ▼
           Embedding Model
                  │
         ┌────────┴────────┐
         ▼                 ▼
     pgvector          BM25 Index
      (dense)           (sparse)
         │                 │
         └────────┬────────┘
                  ▼
            RRF Re-ranker
                  │
                  ▼
          Parent-Child Chunks
                  │
                  ▼
          Llama 3.1 8B (Ollama)
                  │
                  ▼
        Redis Cache ──► User Response
```

**Key decisions & why**

| Decision | Problem solved |
|---|---|
| Ollama / Llama 3.1 8B local | Zero external API cost |
| BM25 + Dense + RRF fusion | Keyword + semantic — best of both |
| Parent-child chunking | Context-boundary loss eliminated |
| Event-driven BM25 re-index | Fixed index staleness → −60% false retrievals |
| Redis response cache | Repeat queries free → −25% inference cost |

**Stack:** `FastAPI` `LangChain` `pgvector` `Ollama` `Redis` `Celery` `PostgreSQL`

</details>

---

<details open>
<summary><b>🛡️ &nbsp;SITS — Smart Inventory Tracking System</b> &nbsp;·&nbsp; <code>Defence · HAL Korwa</code></summary>

<br/>

> Backend owner for India's defence-sector RFID traceability platform

```
              TRANSFER RECONCILIATION
    ─────────────────────────────────────────────

          RFID / Barcode Scan
                  │
                  ▼
           Zone Detection
                  │
                  ▼
          Transfer ID Lookup
                  │
         ┌────────┼────────┐
         ▼        ▼        ▼
       MATCH   SHORT     EXCESS
                RECEIPT  RECEIPT
         │        │        │
         ▼        ▼        ▼
       Commit   Alert    Alert
         │
         ▼
    Audit Trail → PostgreSQL
```

**Key decisions & why**

| Decision | Problem solved |
|---|---|
| Project/batch-aware master data model | Multi-project inventory isolation |
| Zone-based Transfer ID reconciliation | Prevents mis-attribution across zones |
| Match / Short / Excess workflow | Full traceability for military audit |
| Event-driven architecture | Real-time discrepancy alerts |

**Stack:** `Python` `PostgreSQL` `RFID/IoT` `Event-Driven` `RBAC`

</details>

---

<details open>
<summary><b>🔍 &nbsp;VerifyLayer AI</b> &nbsp;·&nbsp; <a href="https://verifylayer-ai.vercel.app/"><code>Live →</code></a> &nbsp;·&nbsp; <code>50K+ Users · 99.2% Accuracy</code></summary>

<br/>

> India's AI scam-detection platform — real-time risk scoring across every attack surface

```
              DETECTION MODULES
    ─────────────────────────────────────────────

     Input ──► WhatsApp / SMS ──► Smishing classifier
           ──► Email           ──► Phishing + spoofing
           ──► Call (audio)    ──► Voice scam patterns
           ──► UPI / QR code   ──► Fraud ID lookup
           ──► Loan App        ──► RBI registry check

                        │
                        ▼
             Risk Aggregation Engine
                        │
             ┌──────────┴──────────┐
             ▼                     ▼
        Risk Score              Verdict
         (0 – 100)      SAFE / SUSPICIOUS / SCAM
```

**Stack:** `FastAPI` `OCR` `NLP` `RBI Registry API` `Risk Scoring Engine`

</details>

---

<details>
<summary><b>⚙️ &nbsp;Zero-Downtime CI/CD Pipeline</b> &nbsp;·&nbsp; <code>30 min → 5 min deployments</code></summary>

<br/>

> Blue-green deployment — zero failed releases since adoption

```
              BLUE-GREEN PIPELINE
    ─────────────────────────────────────────────

           git push
              │
              ▼
     Jenkins Build & Test
              │
              ▼
         Lint / Scan
              │
              ▼
        Docker Image
              │
              ▼
       Push to Registry
              │
      ┌───────┴───────┐
      ▼               ▼
   GREEN env       BLUE env
   (deploy)       (standby)
      │
      ▼
   Health Check 
      │
      ▼
   Nginx Traffic Switch
      │
      ▼
   Blue = new standby
```

**Stack:** `Jenkins` `Docker` `AWS EC2` `AWS S3` `Nginx`

</details>

---

## `$ cat tech_stack.md`

<div align="center">

#### 💻 &nbsp;Languages

<img src="https://skillicons.dev/icons?i=python,java,javascript,typescript,cpp,c,html,css,bash&theme=dark&perline=9" alt="Languages"/>

<br/>

#### ⚙️ &nbsp;Backend & Frameworks

<img src="https://skillicons.dev/icons?i=fastapi,flask,nodejs,express,django&theme=dark&perline=9" alt="Backend"/>

<br/>

#### 🎨 &nbsp;Frontend

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vite&theme=dark&perline=9" alt="Frontend"/>

<br/>

#### 🗄️ &nbsp;Databases

<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,sqlite&theme=dark&perline=9" alt="Databases"/>

<br/>

#### 🤖 &nbsp;AI / ML Stack

<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/BM25-005571?style=for-the-badge&logo=elasticsearch&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>

<br/><br/>

#### ☁️ &nbsp;DevOps & Cloud

<img src="https://skillicons.dev/icons?i=docker,jenkins,aws,githubactions,nginx,linux,grafana&theme=dark&perline=9" alt="DevOps"/>

<br/>

#### 🛠️ &nbsp;Tools

<img src="https://skillicons.dev/icons?i=git,github,postman,vscode&theme=dark&perline=9" alt="Tools"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>

</div>

---

## `$ cat github_stats.md`

<div align="center">

<a href="https://github.com/ChauhanDivyanshu">
  <img src="https://github-readme-stats.vercel.app/api?username=ChauhanDivyanshu&show_icons=true&hide_border=true&bg_color=0F172A&title_color=6366F1&icon_color=8B5CF6&text_color=E2E8F0&count_private=true&include_all_commits=true" height="180" alt="GitHub Stats"/>
</a>
<a href="https://github.com/ChauhanDivyanshu">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ChauhanDivyanshu&layout=compact&hide_border=true&bg_color=0F172A&title_color=6366F1&text_color=E2E8F0&langs_count=8" height="180" alt="Top Languages"/>
</a>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ChauhanDivyanshu&bg_color=0F172A&color=6366F1&line=8B5CF6&point=EC4899&area=true&area_color=6366F1&hide_border=true&custom_title=Contribution+Graph" width="98%" alt="Activity Graph"/>

</div>

---

## `$ git log --oneline career`

```
Mar 2026  feat: joined Infosware as Full Stack Python + AI Developer     ← HEAD
            ├── RAG SaaS Platform shipped to production
            └── SITS (HAL Korwa) — backend owner
            

Apr 2024  feat: QA Software Engineer @ Tekshapers
            ├── 100+ microservices tested end-to-end
            └── NLP pipeline: EPUB QA 3 days → 2 hours

Feb 2024  feat: DevOps Intern @ AR Electricals
            └── CI/CD, Jenkins, Docker — first production pipelines
```

---

## 🐍 Contribution Snake

<div align="center">
  <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%" alt="Contribution Snake"/>
</div>

---

## `$ echo $PHILOSOPHY`

```
> "I don't build demos.
   I ship production systems that handle real traffic,
   real data, and real edge cases."

  ✦  Retrieval quality  >  model size
  ✦  Async by default — sync only when forced
  ✦  Observability is not optional in production
  ✦  Cost optimisation is a feature, not an afterthought
  ✦  If it's not in CI/CD, it doesn't exist
```

---

<div align="center">

### 🤝 Let's Build Something Together

**Open for:** &nbsp; Backend Architecture &nbsp;·&nbsp; RAG & LLM Systems &nbsp;·&nbsp; AI/ML Consulting &nbsp;·&nbsp; Open-Source Collab

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=googlechrome&logoColor=white)](https://divyanshu-chauhan-resume.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iamdivyanshuchauhan)
[![Linktree](https://img.shields.io/badge/Linktree-1A1A1A?style=for-the-badge&logo=linktree&logoColor=43E55E)](https://linktr.ee/Divyanshuchauhan10)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:divyanshuchauhan1200@gmail.com)
[![VerifyLayer AI](https://img.shields.io/badge/VerifyLayer_AI-8B5CF6?style=for-the-badge&logo=shield&logoColor=white)](https://verifylayer-ai.vercel.app/)

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=ChauhanDivyanshu&style=flat-square&color=6366F1&label=profile+views)

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F0C29,50:302B63,100:24243E&height=120&section=footer"/>

</div>
