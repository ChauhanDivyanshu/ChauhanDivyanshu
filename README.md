<!--
  ┌─────────────────────────────────────────────────────────────────┐
  │          DIVYANSHU CHAUHAN — GitHub Profile README              │
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

[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=vercel&logoColor=white)](https://divyanshu-chauhan-resume.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iamdivyanshuchauhan)
[![Linktree](https://img.shields.io/badge/Linktree-1A1A1A?style=for-the-badge&logo=linktree&logoColor=43E55E)](https://linktr.ee/Divyanshuchauhan10)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:divyanshuchauhan1200@gmail.com)
[![VerifyLayer AI](https://img.shields.io/badge/VerifyLayer_AI-8B5CF6?style=for-the-badge&logo=shield&logoColor=white)](https://verifylayer-ai.vercel.app/)

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
<tr>
<td align="center" width="180">

### 🎯 +40%
**Retrieval Accuracy**
<sub>Multi-tier RAG pipeline</sub>

</td>
<td align="center" width="180">

### ⚡ -50%
**Latency Cut**
<sub>Redis + Celery async</sub>

</td>
<td align="center" width="180">

### 💰 -25%
**AI Cost Saved**
<sub>Prompt compression + cache</sub>

</td>
</tr>
<tr>
<td align="center" width="180">

### 🚫 -60%
**False Retrievals**
<sub>Event-driven BM25 re-index</sub>

</td>
<td align="center" width="180">

### 🚀 6x Faster
**Deploy Time**
<sub>30min → 5min · Blue-green</sub>

</td>
<td align="center" width="180">

### 📦 36x Faster
**QA Pipeline**
<sub>3days → 2hrs · NLP EPUB</sub>

</td>
</tr>
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
    ─────────────────────────────────
         User Query ──► Embedding Model
                            │
                 ┌──────────┴──────────┐
                 ▼                     ▼
              pgvector            BM25 Index
               (dense)             (sparse)
                 │                     │
                 └──────────┬──────────┘
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
                   Redis Cache ──► User
```

**Key decisions & why:**

| Decision | Problem solved |
|---|---|
| Ollama / Llama 3.1 8B local | Zero external API cost |
| BM25 + Dense + RRF fusion | Keyword + semantic — best of both |
| Parent-child chunking | Context-boundary loss eliminated |
| Event-driven BM25 re-index | Fixed index staleness → -60% false retrievals |
| Redis response cache | Repeat queries free → -25% inference cost |

**Stack:** `FastAPI` `LangChain` `pgvector` `Ollama` `Redis` `Celery` `PostgreSQL`

</details>

---

<details open>
<summary><b>🛡️ &nbsp;SITS — Smart Inventory Tracking System</b> &nbsp;·&nbsp; <code>Defence · HAL Korwa</code></summary>

<br/>

> Backend owner for India's defence-sector RFID traceability platform

```
              TRANSFER RECONCILIATION
    ─────────────────────────────────
          RFID / Barcode Scan
                  │
                  ▼
           Zone Detection ──► Transfer ID Lookup
                                   │
                       ┌───────────┼───────────┐
                       ▼           ▼           ▼
                     MATCH       SHORT       EXCESS
                                 RECEIPT    RECEIPT
                       │           │           │
                       ▼           ▼           ▼
                     Commit      Alert       Alert
                       │
                       ▼
                 Audit Trail → PostgreSQL
```

**Stack:** `Python` `PostgreSQL` `RFID/IoT` `Event-Driven` `RBAC`

</details>

---

<details open>
<summary><b>🔍 &nbsp;VerifyLayer AI</b> &nbsp;·&nbsp; <a href="https://verifylayer-ai.vercel.app/"><code>Live →</code></a> &nbsp;·&nbsp; <code>50K+ Users · 99.2% Accuracy</code></summary>

<br/>

> India's AI scam-detection platform — real-time risk scoring

```
              DETECTION MODULES
    ─────────────────────────────────
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
    ─────────────────────────────────
              git push
                 │
                 ▼
        Jenkins Build & Test
                 │
                 ▼
           Docker Image → Registry
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
```

**Stack:** `Jenkins` `Docker` `AWS EC2` `AWS S3` `Nginx`

</details>

---

## `$ cat tech_stack.md`

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

<div align="center">

#### 💻 Languages
<img src="https://skillicons.dev/icons?i=python,java,javascript,typescript,cpp,c,html,css,bash&theme=dark&perline=9" alt="languages"/>

#### ⚙️ Backend
<img src="https://skillicons.dev/icons?i=fastapi,flask,nodejs,express,django&theme=dark&perline=5" alt="backend"/>
<br/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white"/>

#### 🎨 Frontend
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vite&theme=dark&perline=5" alt="frontend"/>

#### 🗄️ Databases
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,sqlite&theme=dark&perline=5" alt="databases"/>
<br/>
<img src="https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>

#### 🤖 AI / ML
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/BM25-005571?style=for-the-badge&logo=elasticsearch&logoColor=white"/>

#### ☁️ DevOps
<img src="https://skillicons.dev/icons?i=docker,jenkins,aws,githubactions,nginx,linux,grafana&theme=dark&perline=7" alt="devops"/>

#### 🛠️ Tools
<img src="https://skillicons.dev/icons?i=git,github,postman,vscode&theme=dark&perline=5" alt="tools"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>

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

<a href="https://github.com/ChauhanDivyanshu">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=ChauhanDivyanshu&show_icons=true&hide_border=true&bg_color=0F172A&title_color=6366F1&icon_color=8B5CF6&text_color=E2E8F0&count_private=true&include_all_commits=true" alt="GitHub Stats"/>
</a>
<a href="https://github.com/ChauhanDivyanshu">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ChauhanDivyanshu&layout=compact&hide_border=true&bg_color=0F172A&title_color=6366F1&text_color=E2E8F0&langs_count=8" alt="Top Languages"/>
</a>

<br/><br/>

<img src="https://streak-stats.demolab.com/?user=ChauhanDivyanshu&theme=tokyonight&hide_border=true&background=0F172A&ring=6366F1&fire=8B5CF6&currStreakLabel=6366F1&sideLabels=6366F1&currStreakNum=E2E8F0&sideNums=E2E8F0&dates=64748B" width="70%" alt="Streak"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ChauhanDivyanshu&bg_color=0F172A&color=6366F1&line=8B5CF6&point=EC4899&area=true&area_color=6366F1&hide_border=true&custom_title=Contribution%20Graph" width="96%" alt="Activity Graph"/>

</div>

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

[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=vercel&logoColor=white)](https://divyanshu-chauhan-resume.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iamdivyanshuchauhan)
[![Linktree](https://img.shields.io/badge/Linktree-1A1A1A?style=for-the-badge&logo=linktree&logoColor=43E55E)](https://linktr.ee/Divyanshuchauhan10)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:divyanshuchauhan1200@gmail.com)
[![VerifyLayer AI](https://img.shields.io/badge/VerifyLayer_AI-8B5CF6?style=for-the-badge&logo=shield&logoColor=white)](https://verifylayer-ai.vercel.app/)

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=ChauhanDivyanshu&style=flat-square&color=6366F1&label=profile+views" alt="profile views"/>

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F0C29,50:302B63,100:24243E&height=120&section=footer"/>

</div>
```
