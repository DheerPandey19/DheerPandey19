<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:070A16,55:312E81,100:0E7490&height=220&section=header&text=Dheer%20Pandey&fontSize=62&fontColor=F8FAFC&animation=fadeIn&fontAlignY=40&desc=Small%20models%20%7C%20durable%20agents%20%7C%20systems%20from%20scratch&descSize=16&descAlignY=68" width="100%" alt="Dheer Pandey" />

I take an idea all the way down: a model you can run on a CPU, an agent that remembers where it paused, or a database that actually `fsync`s.

</div>

## About

```yaml
name: Dheer Pandey
focus: applied AI, backend systems, full-stack products
building:
  - small language models that return valid structured JSON
  - agents that stop for a human and resume from Postgres
  - retrieval that mixes vectors with rules you can audit
  - systems learned from the page up, including a key-value store in Go
languages: [Python, Go, TypeScript]
```

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=py,go,ts,fastapi,react,nextjs,postgres,docker,tailwind,sklearn,git,linux&theme=dark&perline=6" alt="Languages and tools" />

<br/>

<img src="https://img.shields.io/badge/LangChain-111827?style=flat-square&logo=langchain&logoColor=67e8f9" alt="LangChain" />
<img src="https://img.shields.io/badge/LangGraph-111827?style=flat-square&logo=langchain&logoColor=a5b4fc" alt="LangGraph" />
<img src="https://img.shields.io/badge/OpenAI-111827?style=flat-square&logo=openai&logoColor=white" alt="OpenAI" />
<img src="https://img.shields.io/badge/llama.cpp-111827?style=flat-square&logoColor=67e8f9" alt="llama.cpp" />
<img src="https://img.shields.io/badge/FAISS-111827?style=flat-square&logoColor=a5b4fc" alt="FAISS" />
<img src="https://img.shields.io/badge/LoRA%20%2F%20GGUF-111827?style=flat-square&logoColor=c4b5fd" alt="LoRA and GGUF" />

</div>

## Selected work

| | |
| --- | --- |
| **[SLM Aspect Sentiment Tagger](https://github.com/DheerPandey19/SLM-based-Sentiment-Analysis-)** | LoRA fine-tune of Qwen2.5-1.5B-Instruct that turns a movie review into structured JSON: overall sentiment plus plot, acting, visuals, pacing, dialogue, soundtrack, and direction. Teacher labels from GPT-4o-mini, local inference through llama.cpp as a Q4_K_M GGUF, and a published pilot eval — including where the base model still wins. |
| **[Email Support Agent](https://github.com/DheerPandey19/Email-Support-Agent)** | LangGraph workflow that classifies mail, looks up docs, drafts a reply, and interrupts for human approve / edit / reject when the case is urgent. Checkpoints live in Postgres, so stopping the server does not lose the thread. FastAPI plus a small review UI. |
| **[CardSense](https://github.com/DheerPandey19/credit-card-assistant-showcase)** | Architecture of a GenAI credit-card assistant: hybrid RAG (FAISS over card facets, Postgres for reward rules), a combinatorial spend optimizer, speculative web enrichment, Langfuse tracing, and RAGAS evaluation. Documentation and diagrams only — [live demo](https://cr-dfa8edf4e50d473db675bd58088bfc86.ecs.ap-south-1.on.aws/). |
| **[Expense Tracker](https://github.com/DheerPandey19/Expense-Tracking-Project)** | Personal finance app. Natural-language logging (`Spent 350 on lunch`), categories, tags, monthly budgets, and a category breakdown. FastAPI, SQLAlchemy, Postgres, React, TypeScript, Tailwind, and an optional Telegram bot on the same database. |
| **[A database in Go](https://github.com/DheerPandey19/building-a-database-in-go)** | Persistent key-value store from scratch: 4KB pages, a copy-on-write B+tree, a free list so updates can recycle pages, and durability via write, `fsync`, meta page, `fsync`. |

<details>
<summary>Earlier experiments</summary>

<br/>

- **[DocTrust QR](https://github.com/DheerPandey19/DocTrust-QR)** — resume and marksheet checks with SHA-256 fingerprints, RSA-wrapped exchange, and a QR handoff between institute, candidate, and recruiter.
- **[Feedback text search](https://github.com/DheerPandey19/FeedBack-Text-Search)** — toy ranker: TF-IDF and cosine similarity, then a boost from the nearest past query whose results a user marked relevant.
- **TaskQuill, a web chatroom, and GigFinder** — earlier Node, EJS, and HTML/CSS apps.

</details>

## GitHub

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=DheerPandey19&show_icons=true&hide_border=true&include_all_commits=true&bg_color=0d1117&title_color=a5b4fc&icon_color=22d3ee&text_color=cbd5e1&ring_color=6366f1" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DheerPandey19&layout=compact&hide_border=true&langs_count=6&bg_color=0d1117&title_color=a5b4fc&text_color=cbd5e1" alt="Top languages" />

</div>

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:0E7490,45:312E81,100:070A16&height=110&section=footer" width="100%" alt="" />
