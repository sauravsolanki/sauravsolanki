# Saurav Solanki

**Machine Learning Engineer · Production LLM systems, agents, and evals**

Senior Software Engineer (ML) at [Sumo Logic](https://www.sumologic.com), co-leading the platform-wide LLM copilot.
Founder of [ML Baba](https://themlbaba.com), where I build production-grade AI systems for SaaS and tech companies.

6+ years shipping ML in product companies, always under real cost and latency constraints.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sauravsolanki-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sauravsolanki/)
[![Email](https://img.shields.io/badge/Email-sausol.solanki%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:sausol.solanki@gmail.com)
[![ML Baba](https://img.shields.io/badge/ML%20Baba-themlbaba.com-111111)](https://themlbaba.com)

---

## What I work on

**Agentic copilot at scale.** Co-led the design of an LLM copilot serving 30K users across 5K enterprise customers. I own context orchestration and the token-efficiency layer (summarization, trimming, prompt caching), which cut response latency 60% and inference cost about 30%.

**Long-term memory for agents.** Architected a shared memory system across org and user scopes. Human-in-the-loop saves plus an observer agent that extracts and consolidates high-signal memories from live conversations. Hybrid retrieval (hot-memory cache plus agentic RAG over a file-like chunk interface) now grounds 30% of user prompts.

**Agent evaluation infrastructure.** Took the eval suite from prototype to production: a capability-aware orchestrator routes agent output to an LLM judge scoring relevance, groundedness, and completeness, sampling low-confidence cases over random draws. Groundedness went from 0.70 to 0.85, completeness from 0.60 to 0.72. Offline eval and regression CI on Phoenix cover 70% of production prompt traffic.

**Retrieval and query understanding.** Hybrid lexical and semantic log-source detection (+50% downstream search throughput) and a sub-500 ms intent service that became the primitive for conversational analytics.

Before this: end-to-end MLOps platform on AWS managing production CV models across 45 client orgs at SenseHawk (Reliance Jio subsidiary), and edge inference optimisation (quantization, pruning, TensorRT, OpenVINO) at DeepEdge.ai.

---

## ML Baba

[**themlbaba.com**](https://themlbaba.com) · *Production-grade AI systems, done right the first time.*

ML Baba helps 20 to 500 person SaaS and tech companies automate operations without building an internal ML team. Reliability, observability, evals, and cost efficiency are built in from day one, not retrofitted. We deploy the system and own the outcome.

What we build:

- **Support automation.** Ticket classification, intent detection, first-response drafting, knowledge-base retrieval.
- **Operations workflows.** Data extraction, record validation, document triage.
- **Data and reporting.** Automated report generation, anomaly detection, reconciliation.

Current products and demos:

| Project | What it is |
|---|---|
| **Production RAG demo** | Live, unattended agentic RAG over the docs of 14 OSS frameworks. Agentic file search with no vector DB, per-library subagents, clickable citations, durable long-term memory in Postgres. Served through chat, Slack, and Zendesk. |
| **Support Ticket Automation** | Streamlit demo of ML-driven ticket triage, classification, routing, and response drafting. [Try it live](https://support-ticket-automation.streamlit.app). |
| **ML Baba Platform** | Multi-tenant core (tenancy, sessions, pipelines, DeepAgent builder with persistent memory, MCP connectors, omnichannel, jobs, analytics, audit trail) with thin vertical plugins. Flagship vertical is US healthcare Revenue Cycle Management. |
| **RCM triage router** | Parses X12 835 remittance files and routes every adjustment line to patient billing, write-off, resubmit, or appeal. Rules in YAML, no LLM, fully tested. |

Want a production AI audit for your team? [Start here](https://themlbaba.com/ai-audit).

---

## Stack

**LLM and agents:** agentic systems, RAG, agent memory, context orchestration, LangChain, LangGraph, deepagents, AWS Bedrock, LLM-as-judge evals, Phoenix / Arize tracing, MCP, OpenSearch, prompt optimisation

**ML and data:** Python, SQL, PyTorch, TensorFlow, scikit-learn, Hugging Face, A/B testing, model monitoring

**Platform:** FastAPI, MLflow, Airflow, Docker, Kubernetes, AWS (Lambda, EKS, S3, SQS, API Gateway), Postgres, MongoDB, Redis, DynamoDB

---

## Background

Integrated M.Tech in Computer Science, Central University of Karnataka (2015 to 2020). Three-time gold medalist (UG, PG, University), awarded by Dr. K. Kasturirangan.
Research intern on MAVI at IIT Delhi, coordinating a six-engineer team building an assistive edge device for the visually impaired.

---

Open to conversations about agent memory, evals, and getting LLM systems to hold up in production.
