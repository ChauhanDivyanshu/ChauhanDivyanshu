<!--
  ┌─────────────────────────────────────────────────────────────────┐
  │          DIVYANSHU CHAUHAN — GitHub Profile README              │
  │     Repo: ChauhanDivyanshu/ChauhanDivyanshu  (README.md)       │
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
[![Linktree](https://img.shields.io/badge/Linktree-39E09B?style=for-the-badge&logo=linktree&logoColor=white)](https://linktr.ee/Divyanshuchauhan10)
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

| Metric | Result | How |
|:---|:---:|:---|
| 🎯 &nbsp; **Retrieval Accuracy** | ![](https://img.shields.io/badge/%2B40%25-6366F1?style=flat-square&labelColor=0F172A) | Multi-tier RAG pipeline |
| ⚡ &nbsp; **Processing Latency** | ![](https://img.shields.io/badge/%E2%88%9250%25-6366F1?style=flat-square&labelColor=0F172A) | Redis + Celery async |
| 💰 &nbsp; **AI Inference Cost** | ![](https://img.shields.io/badge/%E2%88%9225%25-6366F1?style=flat-square&labelColor=0F172A) | Prompt compression + cache |
| 🚫 &nbsp; **False Retrievals** | ![](https://img.shields.io/badge/%E2%88%9260%25-6366F1?style=flat-square&labelColor=0F172A) | Event-driven BM25 re-index |
| 🚀 &nbsp; **Deployment Time** | ![](https://img.shields.io/badge/30min_%E2%86%92_5min-6366F1?style=flat-square&labelColor=0F172A) | Blue-green CI/CD |
| 📦 &nbsp; **QA Pipeline** | ![](https://img.shields.io/badge/3days_%E2%86%92_2hrs-6366F1?style=flat-square&labelColor=0F172A) | NLP EPUB automation |

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
   Health Check ✅
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

## `$ cat stack.json`

```json
{
  "languages"  : ["Python", "Java", "JavaScript", "TypeScript", "C++", "C", "SQL", "Bash", "HTML5", "CSS3"],
  "backend"    : ["FastAPI", "Flask", "Node.js", "Express", "Celery", "LangChain", "Pydantic"],
  "frontend"   : ["React", "Next.js", "Tailwind CSS", "TypeScript"],
  "databases"  : ["PostgreSQL + pgvector", "MySQL", "MongoDB", "Redis", "SQLite"],
  "ai_ml"      : ["Ollama / Llama 3.1", "BM25", "Dense Retrieval", "RRF", "OCR", "NLP", "HuggingFace"],
  "devops"     : ["Docker", "Jenkins", "AWS (EC2/S3)", "GitHub Actions", "Nginx", "Linux"],
  "monitoring" : ["Grafana", "Structured logging", "Health-check endpoints"],
  "tools"      : ["Git", "GitHub", "Postman", "VS Code", "Jupyter"]
}
```

---

## `$ cat github_stats.md`

<div align="center">

<img src="https://streak-stats.demolab.com/?user=ChauhanDivyanshu&theme=tokyonight&hide_border=true&background=0F172A&ring=6366F1&fire=8B5CF6&currStreakLabel=6366F1" width="70%" alt="GitHub Streak"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ChauhanDivyanshu&bg_color=0F172A&color=6366F1&line=8B5CF6&point=EC4899&area=true&area_color=6366F1&hide_border=true&custom_title=Contribution+Graph" width="96%" alt="Activity Graph"/>

</div>

---

## `$ git log --oneline career`

```
Mar 2026  feat: joined Infosware as Full Stack Python + AI Developer     ← HEAD
            ├── RAG SaaS Platform shipped to production
            ├── SITS (HAL Korwa) — backend owner
            └── VerifyLayer AI — 50K+ users protected

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
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:divyanshuchauhan1200@gmail.com)
[![VerifyLayer AI](https://img.shields.io/badge/VerifyLayer_AI-8B5CF6?style=for-the-badge&logo=shield&logoColor=white)](https://verifylayer-ai.vercel.app/)

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=ChauhanDivyanshu&style=flat-square&color=6366F1&label=profile+views)

</div>
