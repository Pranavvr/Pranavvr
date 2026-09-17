<h1 align="center">Pranav Raghavendra Rao</h1>

<p align="center">
  <b>AI / ML Engineer &middot; Research Engineer &middot; Data Scientist</b><br>
  <sub>Models, and the production systems around them</sub>
</p>

<p align="center">
  <sub>
    Python &middot; SQL &middot; PyTorch &middot; TensorFlow &middot; scikit-learn &middot; CUDA &middot; Spark<br>
    LangGraph &middot; vLLM &middot; PostgreSQL &middot; Redis &middot; AWS &middot; Azure &middot; Docker &middot; Terraform &middot; MLflow
  </sub>
</p>

<p align="center">
  <a href="https://pranavvr.github.io/"><img src="https://img.shields.io/badge/Portfolio-pranavvr.github.io-0d9488?style=flat-square" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/pranav-raghavendra-rao-b5992618b/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:pranav.raghavrao@gmail.com"><img src="https://img.shields.io/badge/Email-pranav.raghavrao@gmail.com-c14438?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

I work close to the people who depend on what I build — wind fleet operators, pharma QA teams,
clinical researchers, retail planners. Classical ML, deep learning, and the software around both:
typed interfaces, unit tests, CI, infrastructure as code, and evaluation harnesses that measure
outcomes rather than the model's own account of them.

Currently **AI Research Engineer at Yale**, building clinical research infrastructure. Previously
**Boehringer Ingelheim**, **Berkshire Hathaway Energy**, and two years as a Data Scientist at
**Deloitte**. M.S. Data Science, Northeastern.

### Stack

**Modeling & statistics** PyTorch · TensorFlow · scikit-learn · CUDA · Spark · distributed training · clustering · hypothesis testing
**GenAI & agents** RAG · agentic systems · inference optimization · vector DBs · LangGraph · LangChain · LangSmith · RAGAS · vLLM · MCP
**Languages & data** Python · TypeScript · R · C/C++ · SQL · PostgreSQL · MongoDB · Redis
**Engineering & infra** tests · CI/CD · Terraform · Docker · FastAPI · Pydantic · Alembic · MLflow · Airflow · AWS · Azure

### Things I've built

**[Calendar.ai](https://github.com/Pranavvr/Calendar.ai)** — turns *"gym, study 2 hours, groceries"* into a booked day that doesn't double-book you. The calendar tools are closed over a per-user client, so the model never sees a user ID and cross-tenant access is structurally impossible rather than prompt-dependent. Evals score the resulting calendar state, not the model's account of what it did.
<br><sub>`LangGraph` `OAuth 2.0` `Terraform` `ECS Fargate` — 82 tests, 10 ADRs</sub>

**[voice-agent](https://github.com/Pranavvr/voice-agent)** — runs mock interviews over voice, then grades how you did. Transcripts accumulate in Redis while the session is live and migrate to PostgreSQL on completion, because real-time audio punishes latency anywhere in the path.
<br><sub>`OpenAI Realtime` `WebSockets` `Redis` `PostgreSQL`</sub>

**[Repo_Explainer_MCP](https://github.com/Pranavvr/Repo_Explainer_MCP)** — Copilot and Cursor reason about your repo from stale training data. This gives them the live one: five tools over the GitHub API, no cloning, read-only token scope by design. Published to PyPI.
<br><sub>`MCP` `Python` `GitHub API` `PyPI`</sub>

**[Smart_Investor_Agent](https://github.com/Pranavvr/Smart_Investor_Agent)** — investment answers grounded in real market data, with Airflow scheduling ingestion so the data doesn't quietly go stale.
<br><sub>`RAG` `Vector search` `Airflow` `FastAPI`</sub>

---

<p align="center">
  <sub>Longer write-ups at <a href="https://pranavvr.github.io/">pranavvr.github.io</a> &middot;
  <a href="mailto:pranav.raghavrao@gmail.com">pranav.raghavrao@gmail.com</a></sub>
</p>
