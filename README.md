# Saurav Solanki

**Machine Learning Engineer · 6+ years**  Bangalore, India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sauravsolanki-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sauravsolanki/)
[![Email](https://img.shields.io/badge/Email-sausol.solanki%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:sausol.solanki@gmail.com)

Machine learning engineer with 6+ years in product companies, shipping AI systems that hold up in production under real cost and latency constraints. Currently co-leading the platform-wide LLM copilot at Sumo Logic, owning long-term memory, agent evaluation infrastructure, and token efficiency. Partners across cross-geo engineering teams and directly with enterprise customers.

---

## Experience

### Sumo Logic — Senior Software Engineer I (Machine Learning)
*Cloud-native log management and observability platform · Nov 2024 – Present · Remote*

- **Agentic AI Copilot.** Co-led design of the platform-wide LLM copilot serving **30K users across 5K enterprise customers**. Owned context orchestration and the token-efficiency layer (summarization, trimming, prompt caching), cutting **response latency 60%** and **inference cost ~30%**.
- **Long-Term Memory.** Architected a shared memory system spanning org and user scopes, pairing human-in-the-loop saves with an observer agent that extracts and consolidates high-signal memories from live conversation. Hybrid retrieval (top-50 hot-memory cache plus agentic RAG over a file-like chunk interface) grounds **30% of user prompts** and cut reference latency **from 12 minutes to 4 minutes**. Shipped across all agents.
- **Agent Evaluation Platform.** Took the eval suite from prototype to production grade: a capability-aware orchestrator routing agent output to an LLM judge scoring relevance, groundedness, and completeness, deliberately sampling low-confidence cases over random draws. Raised **groundedness 0.70 → 0.85** and **completeness 0.60 → 0.72** across all agents.
- **Offline Eval and Regression CI.** Built an offline eval pipeline from happy/sad-path cases mined from live judge metrics (no-data handling, exploratory queries, agent tone, multi-hypothesis reasoning), covering **70% of production prompt traffic** and wired into CI/CD for regression tracking. A unified API/local eval interface on Phoenix cut the improvement cycle **from weeks to days**.
- **Retrieval and Query Understanding.** Owned a 2-second log-source detection pipeline using hybrid lexical and semantic retrieval (**+50% downstream search throughput**) and a sub-500 ms intent service that became the foundational primitive for conversational analytics (**+70% query interpretation accuracy**).

### SenseHawk — Software Engineer, Machine Learning
*Solar digitization platform, Reliance Jio subsidiary · Feb 2023 – Nov 2024 · Remote*

- **End-to-End MLOps Platform.** Co-led design of an automated MLOps system on AWS managing **5 production models across 45 client orgs**, owning the full lifecycle (training, registry, versioning, serving, model selection, data and model drift detection) and collapsing **ML cycle time 90%**. Partnered directly with the CTO on ML direction.
- **Production Computer Vision.** Cut weekly construction-site reporting time **70%** by deploying YOLOv8, U-Net, SAM, transformers, and GPT-based models over **~10 TB/week of drone imagery** across thousands of solar sites.
- **Distributed Integration Service.** Built an event-driven OAuth 2.0 integration microservice (FastAPI, Airflow, AMQ/SQS, AWS S3, Lambda) powering **5K+ customer integrations** and sustaining **1,000+ concurrent jobs** via Microsoft Graph and AutoCAD.

### DeepEdge.ai — Software Engineer, Machine Learning
*Edge AI / MLOps platform for industrial computer vision · Jun 2021 – Feb 2023 · Hyderabad*

- **Edge Inference and Fleet Platform.** Lifted on-device inference **25–30%** via quantization (QAT, TFLite, TensorRT, OpenVINO) and structured pruning on resource-constrained hardware. Architected the web platform for real-time edge device operations (provisioning, telemetry, jobs, alerts, logs), cutting **model management time 80%**.

---

## Skills

| | |
|---|---|
| **LLM and Agents** | Agentic systems, RAG, agent memory architectures, context orchestration, LangChain, LangGraph, AWS Bedrock, LLM-as-judge evaluation, Phoenix/Arize tracing, MCP, OpenSearch, prompt optimization |
| **ML and Data** | Python, SQL, PyTorch, TensorFlow, scikit-learn, Hugging Face, CI/CD, A/B testing, model monitoring |
| **Platform** | FastAPI, MLflow, Airflow, Docker, Kubernetes, AWS (Lambda, EKS, S3, SQS, API Gateway), MongoDB, Redis, DynamoDB |

---

## Education

**Central University of Karnataka** — Integrated M.Tech, Computer Science (2015 – 2020)
UG 84.9% · PG 95.8% · **3x Gold Medalist** (UG, PG, University), awarded by ISRO Chief Dr. K. Kasturirangan.

**Research Intern, MAVI — IIT Delhi** (Aug 2019 – Aug 2020)
Coordinated a 6-engineer team building an assistive edge device for the visually impaired: task allocation, systems integration, and professor liaison. Architected the inference pipeline for **40–70% faster on-device processing**.
