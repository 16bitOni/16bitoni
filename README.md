<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f2937,100:6366f1&height=190&section=header&text=Subhadip&fontSize=62&fontColor=ffffff&fontAlignY=38&desc=I%20build%20AI%20systems%20that%20act%2C%20not%20just%20answer&descSize=17&descAlignY=60&animation=fadeIn" width="100%" alt="header" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=2800&pause=900&color=A5B4FC&center=true&vCenter=true&width=640&lines=agents+that+use+tools+%E2%86%92+LangGraph+%2B+Bedrock;fine-tuning+small+models+%E2%86%92+QLoRA+%2B+evals;serving+LLMs+at+load+%E2%86%92+vLLM;C+extensions+on+PyPI+%E2%86%92+yes%2C+really;firmware+that+flies+%E2%86%92+STM32+%2B+ESP32" alt="typing" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/subhadipmondal89)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:subhadipmondal789@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/subhadip_x86)
![Location](https://img.shields.io/badge/Kolkata%2C_India-111827?style=flat-square&logo=googlemaps&logoColor=white)
![Status](https://img.shields.io/badge/open_to-FDE_%2F_Applied_AI_roles-6366f1?style=flat-square)

</div>

---

```python
class Subhadip:
    location   = "Kolkata, India"
    education  = "B.E. Electronics & Communication, Chandigarh University"
    day_jobs   = ["AI Tutor @ xAI", "freelance AI agents + circuit design"]
    roots      = "Bengal"
    languages  = ["Python", "C/C++", "TypeScript", "Elixir", "Solidity"]
    obsessions = ["agents", "evals", "inference", "embedded systems"]
    looking_for = "Forward Deployed / Applied AI Engineer, early-stage, remote"
    long_game  = "found something of my own"

    def current_mode(self):
        return "ship > talk"
```

## 🔭 What I'm building right now

| Project | What it is | Stack |
|---|---|---|
| **Riki** | Multi-agent personal assistant. A supervisor routes work to planner, researcher and memory-keeper agents. Tiered long-term memory with hybrid retrieval. Includes a *Desktop Operator* that sees the screen, plans and acts on a real Windows desktop, with an allowlist and approval for risky steps. | FastAPI · LangGraph · AWS Bedrock · Postgres/pgvector · SQLAlchemy 2.0 async |
| **Handoff** | My entry for the Amazon Devices hackathon, Alexa+ track, built on the Desktop Operator work. | Python · Alexa+ |
| **Multi-tenant LLM inference** | Serving open models to many concurrent users: vLLM, hot-swappable LoRA adapters, and a proper load-characterization suite. | vLLM · LoRA · AWS |
| **Text-to-SQL with guardrails** | Fine-tuned small-model pipeline with a held-out eval harness (55 questions over Chinook) and checks that the SQL actually answers the question asked. | QLoRA · SageMaker · SQLite |
| **Job Radar** | Pulls Greenhouse, Lever and Ashby boards daily, classifies roles and detects hiring signals. I'm user #1: it finds me remote USD roles. | Python · scraping · classification |

```mermaid
flowchart LR
    U([You]) --> S{{Supervisor}}
    S --> P[Planner]
    S --> R[Researcher]
    S --> M[Memory keeper]
    M <--> DB[(Postgres + pgvector)]
    M <--> S3[(S3 source of truth)]
    S --> D[Desktop Operator]
    D -->|screenshot| V[Vision]
    V -->|plan| D
    D -->|approved actions| W[Windows desktop]
```

## 🧪 Shipped

- **DipCompress**: a compression package with C extensions, published on PyPI. Wheels built with `cibuildwheel` and released through GitHub Actions OIDC trusted publishing, no tokens in secrets.
- **[DocPilot](https://github.com/16bitOni/docpilot)**: collaborative document AI platform. React + TypeScript front end, FastAPI back end, Supabase Postgres, Pinecone. [Live demo](https://docpilot-livid.vercel.app).
- **[Gmail Assistant](https://github.com/16bitOni/gmail_assistant)**: an LLM agent that reads inbox threads and chains tools across web search, Google Calendar, Slack and reply drafting.
- **QLoRA fine-tunes**: Phi-2 and Phi-3 for text-to-SQL, trained on SageMaker GPUs.
- **RAG and agent pipelines** in production-shaped form.

## 🛠️ Hardware side quest

Before the LLM era I was doing firmware and PCBs at a drone startup: **STM32 / ESP32** firmware, **KiCad** board design and **RTSP** video streaming. I still do circuit design on the side. It keeps my software honest about latency, memory and things that physically break.

## 🧰 Toolbox

<div align="center">

![Python](https://skillicons.dev/icons?i=python,c,cpp,ts,js,elixir&theme=dark)
![Backend](https://skillicons.dev/icons?i=fastapi,nodejs,express,postgres,mongodb,mysql,sqlite,elasticsearch&theme=dark)
![AI](https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv,pandas,numpy&theme=dark)
![Cloud](https://skillicons.dev/icons?i=aws,gcp,firebase,docker,git,github,vercel,netlify&theme=dark)
![Hardware](https://skillicons.dev/icons?i=arduino,raspberrypi,linux&theme=dark)

</div>

<details>
<summary><b>The full list, including the less glamorous parts</b></summary>

<br/>

| Area | Things I use |
|---|---|
| **LLM / agents** | LangGraph, AWS Bedrock, tool use, MCP, RAG (hybrid retrieval), evals, QLoRA / Unsloth, vLLM |
| **ML** | PyTorch, TensorFlow, Keras, scikit-learn, SciPy, MLflow, CUDA |
| **Data** | Pandas, NumPy, Plotly, Matplotlib, SQL |
| **Backend** | FastAPI, Node / Express, Next.js, EJS, SQLAlchemy, Alembic, Pydantic |
| **Datastores** | Postgres + pgvector, MongoDB, MySQL, SQLite, Elasticsearch, Pinecone, Firebase |
| **Infra** | AWS, GCP, Docker, GitHub Actions, Render, Heroku, Netlify, Vercel |
| **Systems / HW** | C, C++, STM32, ESP32, Arduino, KiCad, FFmpeg, OpenCV |
| **Other** | Elixir, Solidity, Notion, Git |

</details>

## 📊 Numbers, for the people who like numbers

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=16bitOni&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&show_icons=true" alt="stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=16bitOni&theme=tokyonight&hide_border=true&layout=compact&langs_count=8" alt="languages" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=16bitOni&theme=tokyonight&hide_border=true" alt="streak" />

</div>

## 🎯 Working with me

I'm after **Forward Deployed Engineer** and **Applied AI Engineer** roles at early-stage startups, remote preferred. I'm at my best when the problem is messy and the customer is real: take a vague need, build the thing, put it in front of users, measure it honestly.

Good reasons to message me:
- you need an agent that works on real tasks, not just demos
- you want a model fine-tuned, served and evaluated end to end
- your product touches hardware and AI at the same time
- you're building something early and need someone who ships

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:1f2937,100:0d1117&height=110&section=footer" width="100%" alt="footer" />

<sub>Built in Kolkata. Powered by chai and stubbornness.</sub>

</div>
