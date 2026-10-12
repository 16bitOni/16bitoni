<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050510,40:1a0030,100:4a0060&height=180&section=header&text=%20&fontSize=1" width="100%"/>

</div>

```
  ╔══════════════════════════════════════════════════════════════════╗
  ║                    ▄██▄   ▄██▄                                   ║
  ║                   ██████ ██████                                  ║
  ║              ▄████████████████████▄                              ║
  ║            ██  ░░░░░░░░░░░░░░░░░░  ██                           ║
  ║           ██    ▒▓███▒   ▒▓███▒     ██                          ║
  ║           ██     ▀███▀   ▀███▀      ██                          ║
  ║           ██       ░░  ▽  ░░        ██                          ║
  ║           ██    ╔══════════════╗    ██                          ║
  ║            ██   ║▐▌ ▐▌ ▐▌ ▐▌  ║   ██                           ║
  ║             ▀██ ╚══════════════╝ ██▀                            ║
  ║                                                                  ║
  ║         SUBHADIP  ·  16bitOni  ·  鬼  ·  DAEMON ENGINEER        ║
  ╚══════════════════════════════════════════════════════════════════╝
```

<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=15&duration=2800&pause=900&color=CC44FF&center=true&vCenter=true&width=640&lines=agents+that+use+tools+%E2%86%92+LangGraph+%2B+Bedrock;fine-tuning+small+models+%E2%86%92+QLoRA+%2B+evals;serving+LLMs+at+load+%E2%86%92+vLLM;C+extensions+on+PyPI+%E2%86%92+yes%2C+really;firmware+that+flies+%E2%86%92+STM32+%2B+ESP32" alt="typing" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/subhadipmondal89)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:subhadipmondal789@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/subhadip_x86)
![Location](https://img.shields.io/badge/Kolkata%2C_India-0d0010?style=flat-square&logo=googlemaps&logoColor=CC44FF)

</div>

---

```bash
$ oni --boot --mode=engineer

[████████████████████] 100%

  IDENTITY .......... subhadip mondal
  ALIAS ............. 16bitOni  /  鬼
  ORIGIN ............ kolkata, bengal, india
  SUBSTRATE ......... B.E. ECE, Chandigarh University
  CURRENT OPS ....... AI Tutor @ xAI  ·  freelance agents  ·  circuits
  LANGUAGES ......... Python  ·  C/C++  ·  TypeScript  ·  Elixir  ·  Solidity
  DIRECTIVE ......... ship > talk

> daemon loaded. systems nominal.
```

---

## ⚙ ACTIVE PROCESSES

```
 PID    DAEMON               STATUS      STACK
 ─────────────────────────────────────────────────────────────────────────────
 0x001  riki                 RUNNING ▶   LangGraph · Bedrock · Postgres/pgvector
                             ↳ supervisor routes work: planner · researcher · memory-keeper
                             ↳ Desktop Operator: sees screen, plans, acts on Windows
                             ↳ tiered long-term memory + hybrid retrieval

 0x002  handoff              TESTING ▶   Python · Alexa+
                             ↳ Amazon Devices hackathon · Alexa+ track
                             ↳ built on top of Desktop Operator

 0x003  llm-inference-mt     RUNNING ▶   vLLM · hot-swap LoRA · AWS
                             ↳ serving open models to concurrent users
                             ↳ load-characterization suite included

 0x004  text-to-sql          RUNNING ▶   QLoRA · SageMaker · SQLite
                             ↳ fine-tuned small-model pipeline
                             ↳ 55-question eval harness over Chinook

 0x005  job-radar            RUNNING ▶   Python · scraping · classification
                             ↳ pulls Greenhouse + Lever + Ashby daily
                             ↳ I am user #1
```

```mermaid
flowchart LR
    style U fill:#1a0033,color:#ff44ff,stroke:#7c3aed
    style S fill:#1a0033,color:#c084fc,stroke:#7c3aed
    style P fill:#0d1117,color:#c4b5fd,stroke:#4c1d95
    style R fill:#0d1117,color:#c4b5fd,stroke:#4c1d95
    style M fill:#0d1117,color:#c4b5fd,stroke:#4c1d95
    style D fill:#0d1117,color:#c4b5fd,stroke:#4c1d95
    style DB fill:#050510,color:#818cf8,stroke:#4c1d95
    style S3 fill:#050510,color:#818cf8,stroke:#4c1d95
    style V fill:#0d1117,color:#c4b5fd,stroke:#4c1d95
    style W fill:#0d1117,color:#c4b5fd,stroke:#4c1d95

    U([鬼]) --> S{{Supervisor}}
    S --> P[Planner]
    S --> R[Researcher]
    S --> M[Memory]
    M <--> DB[(pgvector)]
    M <--> S3[(S3)]
    S --> D[Desktop Op]
    D -->|screenshot| V[Vision]
    V -->|plan| D
    D -->|approved actions| W[Windows]
```

---

## 🗡 ARTIFACTS  *(shipped, real, in the wild)*

| artifact | what it is |
|---|---|
| **DipCompress** | compression lib with C extensions · published on PyPI · wheels via `cibuildwheel` · OIDC trusted publishing, zero tokens in secrets |
| **[DocPilot](https://github.com/16bitOni/docpilot)** | collaborative document AI · React + TypeScript front end · FastAPI back end · Supabase + Pinecone · [live ↗](https://docpilot-livid.vercel.app) |
| **[Gmail Assistant](https://github.com/16bitOni/gmail_assistant)** | LLM agent over inbox threads · chains web search · Google Calendar · Slack · reply drafting |
| **QLoRA fine-tunes** | Phi-2 + Phi-3 for text-to-SQL · trained on SageMaker GPUs · eval harness included |
| **RAG + agent pipelines** | production-shaped · not toy demos |

---

## ⚡ PHYSICAL LAYER

```
before the LLM era, the work was in the metal.

drone startup — STM32 + ESP32 firmware · KiCad board design · RTSP video streaming.
still do circuit design on the side.
it keeps the software honest about latency, memory, and things that physically break.
```

---

## 🔮 ARSENAL

<div align="center">

![Python](https://skillicons.dev/icons?i=python,c,cpp,ts,js,elixir&theme=dark)
![Backend](https://skillicons.dev/icons?i=fastapi,nodejs,express,postgres,mongodb,mysql,sqlite,elasticsearch&theme=dark)
![AI](https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv,pandas,numpy&theme=dark)
![Cloud](https://skillicons.dev/icons?i=aws,gcp,firebase,docker,git,github,vercel,netlify&theme=dark)
![Hardware](https://skillicons.dev/icons?i=arduino,raspberrypi,linux&theme=dark)

</div>

<details>
<summary><b>▶ open grimoire</b></summary>

<br/>

| domain | weapons |
|---|---|
| **LLM / agents** | LangGraph · AWS Bedrock · tool use · MCP · RAG (hybrid retrieval) · evals · QLoRA · Unsloth · vLLM |
| **ML** | PyTorch · TensorFlow · Keras · scikit-learn · SciPy · MLflow · CUDA |
| **data** | Pandas · NumPy · Plotly · Matplotlib · SQL |
| **backend** | FastAPI · Node/Express · Next.js · EJS · SQLAlchemy · Alembic · Pydantic |
| **datastores** | Postgres + pgvector · MongoDB · MySQL · SQLite · Elasticsearch · Pinecone · Firebase |
| **infra** | AWS · GCP · Docker · GitHub Actions · Render · Heroku · Vercel · Netlify |
| **systems / hw** | C · C++ · STM32 · ESP32 · Arduino · KiCad · FFmpeg · OpenCV |
| **other** | Elixir · Solidity · Git |

</details>

---

## 📡 SIGNAL

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=16bitOni&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&show_icons=true" alt="stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=16bitOni&theme=tokyonight&hide_border=true&layout=compact&langs_count=8" alt="languages" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=16bitOni&theme=tokyonight&hide_border=true" alt="streak" />

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4a0060,50:1a0030,100:050510&height=110&section=footer" width="100%"/>

```
PROCESS 16bitOni  —  STATUS: RUNNING  —  UPTIME: ∞  —  ORIGIN: kolkata, bengal
```

<sub>built here. powered by chai and stubbornness.</sub>

</div>
