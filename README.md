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
[![Linktree](https://img.shields.io/badge/Linktree-1A1A1A?style=for-the-badge&logo=linktree&logoColor=43E55E)](https://linktr.ee/Divyanshuchauhan10)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:divyanshuchauhan1200@gmail.com)
[![VerifyLayer](https://img.shields.io/badge/VerifyLayer_AI-8B5CF6?style=for-the-badge&logo=shield&logoColor=white)](https://verifylayer-ai.vercel.app/)

</div>

<br/>

---

## `$ whoami`

```python
class DivyanshuChauhan:

    role     = "Full Stack Python Developer · AI Engineer"
    company  = "Infosware Private Limited, Noida 🇮🇳"
    focus    = ["RAG Systems", "LLM in Production", "Backend Architecture"]

    currently = {
        "building" : [
            "White-Label RAG SaaS — Ollama · Llama 3.1 · pgvector · LangChain",
            "SITS — Defence inventory backend for HAL Korwa Avionics",
            "VerifyLayer AI — Scam detection · 50K+ users · 99.2% accuracy",
        ],
        "learning" : ["Agentic RAG", "Multi-modal retrieval", "eBPF observability"],
        "open_to"  : ["Backend roles", "AI/ML engineering", "Open-source collab"],
    }

    principles = [
        "Retrieval quality > model size",
        "Async by default, sync when forced",
        "Ship → measure → cut cost → repeat",
        "If it's not observable, it doesn't exist",
    ]
```

---

## `$ cat metrics.log`

<div align="center">

<table>
  <thead>
    <tr>
      <th align="left" width="250">Metric</th>
      <th align="center" width="180">Result</th>
      <th align="left" width="280">How</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>🎯 &nbsp; <b>Retrieval Accuracy</b></td>
      <td align="center"><code>+40%</code></td>
      <td>Multi-tier RAG pipeline</td>
    </tr>
    <tr>
      <td>⚡ &nbsp; <b>Processing Latency</b></td>
      <td align="center"><code>−50%</code></td>
      <td>Redis + Celery async workers</td>
    </tr>
    <tr>
      <td>💰 &nbsp; <b>AI Inference Cost</b></td>
      <td align="center"><code>−25%</code></td>
      <td>Prompt compression + response cache</td>
    </tr>
    <tr>
      <td>🚫 &nbsp; <b>False Retrievals</b></td>
      <td align="center"><code>−60%</code></td>
      <td>Event-driven BM25 re-indexing</td>
    </tr>
    <tr>
      <td>🚀 &nbsp; <b>Deployment Time</b></td>
      <td align="center"><code>30 min → 5 min</code></td>
      <td>Blue-green CI/CD pipeline</td>
    </tr>
    <tr>
      <td>📦 &nbsp; <b>Accessibility QA</b></td>
      <td align="center"><code>3 days → 2 hrs</code></td>
      <td>Python NLP pipeline for EPUB</td>
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

**Key decisions & why:**

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

**Key decisions & why:**

| Decision | Problem solved |
|---|---|
| Project/batch-aware master data model | Multi-project inventory isolation |
| Zone-based Transfer ID reconciliation | Prevents mis-attribution across zones |
| Match/Short/Excess receipt workflow | Full traceability for military audit |
| Event-driven architecture | Real-time discrepancy alerts |

**Stack:** `Python` `PostgreSQL` `RFID/IoT` `Event-Driven` `Role-Based Access`

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

#### 🤖 &nbsp;AI / ML

![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

<br/>

#### ☁️ &nbsp;DevOps & Cloud

<img src="https://skillicons.dev/icons?i=docker,jenkins,aws,githubactions,nginx,linux,grafana&theme=dark&perline=9" alt="DevOps"/>

<br/>

#### 🛠️ &nbsp;Tools

<img src="https://skillicons.dev/icons?i=git,github,postman,vscode&theme=dark&perline=9" alt="Tools"/>

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

## `$ cat github_stats.md`

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ChauhanDivyanshu&bg_color=0F172A&color=6366F1&line=8B5CF6&point=EC4899&area=true&area_color=6366F1&hide_border=true&custom_title=Contribution+Graph" width="98%" alt="Activity Graph"/>

</div>

---

## `$ ./snake --watch`

<div align="center">
  <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%" alt="Snake Animation"/>
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

**Open for:** &nbsp; Backend Architecture &nbsp;·&nbsp; RAG & LLM Systems &nbsp;·&nbsp; AI/ML Consulting &nbsp;·&nbsp; Open-Source Collab

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=googlechrome&logoColor=white)](https://divyanshu-chauhan-resume.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iamdivyanshuchauhan)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:divyanshuchauhan1200@gmail.com)
[![VerifyLayer AI](https://img.shields.io/badge/VerifyLayer_AI-8B5CF6?style=for-the-badge&logo=shield&logoColor=white)](https://verifylayer-ai.vercel.app/)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=ChauhanDivyanshu&style=flat-square&color=6366F1&label=profile+views)

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F0C29,50:302B63,100:24243E&height=120&section=footer"/>

</div>
