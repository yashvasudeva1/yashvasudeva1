<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/header-light.svg" />
  <img alt="Yash Vasudeva — Machine Learning Engineer" src="./assets/header-light.svg" width="100%" />
</picture>

<br />

I build ML and retrieval systems, fine-tune small language models, and spend a slightly unreasonable amount of time testing whether popular ML advice actually works. B.Tech IT student in Delhi; previously interned at Tata Power DDL building electricity theft detection models.

Most repos here started as either a production pipeline or a workflow that annoyed me enough to automate. When I run controlled benchmarks on prompting, preprocessing, or scaling, I put the write-ups on [yashvasudeva.app/blog](https://yashvasudeva.app/blog) (the boring baseline wins more often than it should).

### Selected builds

| Build | What it is |
| :--- | :--- |
| [**qwen-data-science-instruct**](https://github.com/yashvasudeva1/qwen-data-science-instruct) | `Qwen2.5-3B-Instruct` fine-tuned on 16.4K data science examples with 4-bit QLoRA (Unsloth) on a single T4. 86% win rate over base (+109.5% BLEU, +66.9% ROUGE-L). |
| [**Nexus (Adaptive RAG)**](https://github.com/yashvasudeva1/Production-oriented-adaptive-RAG) | Confidence-gated hybrid retrieval (Qdrant HNSW + BM25, calibrated RRF, cross-encoder reranking). 97.3% abstention accuracy on unanswerable queries, 186 tests passing. |
| [**ntl-detection**](https://github.com/yashvasudeva1/ntl-detection) | Electricity theft and meter tampering detection from my Tata Power DDL internship. Tuned to a 65%+ audit precision floor across 10K consumers because false-positive field raids cost real money. |
| [**ResumeDojo**](https://github.com/yashvasudeva1/Resume_ops) | Resume parser and ATS auditor built with Docling, PyMuPDF, FastAPI, and Next.js. Pulls out factual structure first, then scores bullets against 12+ tech roles without polite fluff. |
| [**ORCHESTRA**](https://github.com/yashvasudeva1/ORCHESTRA) · [live](https://orchestra-eosin.vercel.app) | Upload a CSV of hackathon submissions; five judge agents, a bias auditor, and a chief judge review the repos and return a ranked leaderboard. |

### Day-to-day stack

- **Modeling & eval:** Python, PyTorch, scikit-learn, XGBoost, Unsloth, QLoRA, Hugging Face
- **Retrieval & backend:** FastAPI, Qdrant, PostgreSQL, SQLite, LangChain, Docling
- **Web & data:** TypeScript, Next.js, Node.js, Pandas, SQL

---

[yashvasudeva.app](https://yashvasudeva.app) · [Writing](https://yashvasudeva.app/blog) · [LinkedIn](https://www.linkedin.com/in/yash-vasudeva/) · [X](https://x.com/YashVasudeva2)
