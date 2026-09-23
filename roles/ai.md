# AI / LLM Infrastructure

Modular LLMs, dynamic hybrid RAG, agents, STT/TTS, MCP, and AI-backed developer workflows.

[Email](mailto:Kingreqle@gmail.com) · [GitHub](https://github.com/itzreqle) · [flowbit](https://github.com/flowbit-io) · [Profile README](../README.md)

## Summary

AI infrastructure specialization layered on strong platform and backend engineering: modular model routing, hybrid RAG across multiple vector stores, multi-agent orchestration, Whisper-based voice pipelines, MCP/agent harnesses, and production Telegram AI bots. Supports—not replaces—the Cloud / Platform identity.

## Relevant experience

### Founder & CTO · [flowbit](../experience/flowbit.md) · Remote · 2024 – Present

- Architected modular LLM systems that reduced inference costs by **~25%** and intelligent agents that automated over **100 hours** of manual work per month.
- Advanced agentic developer experience with vendored coding-agent surfaces (Zed, OpenCode, Cline) and exploration of shared agent harnesses, parallel agents, and model routing for platform DX.
- Operated local AI inference (Ollama, MLX) on Apple Silicon, applying model memory-versus-disk-size constraints to inform AIaaS product and gateway design.
- Built agentic CI/CD workflows: GitHub Actions + Gemini for PR/branch summaries; Cursor and Claude agents for PR/commit/task analysis; repo `AGENTS.md` / `SKILL.md`, MCP tool servers, sub-agents, and sandboxed harnesses with human review so secrets never enter models.
- Integrated multi-provider AI surfaces (OpenAI, Anthropic, Hugging Face Hub/Inference, Higgsfield generative media API) and offline STT/TTS stacks (OpenAI Whisper / faster-whisper and related speech models) for voice experiences on dedicated servers.
- Advanced AIaaS product direction with knowledge-base / RAG configuration UX and guardrails.

### Full-Stack / Platform Engineer · [Enterprise BPMN ERP](../experience/enterprise-bpmn-erp.md) · Remote · 2025 – 2026 *(concurrent)*

- Integrated external AI services for HR and interview augmentation (resume extraction, job-description generation, AI-assisted assessments), advancing AI-augmented ERP capabilities.

### Freelance · [Freelance](../experience/freelance.md) · Remote · 2018 – Present

- Designed and operated three Telegram AI bots (OpenAI ChatGPT wrapper, Anthropic Claude wrapper, English-to-Persian NLP translation/grammar bot), serving roughly **1,000–2,000** free-tier users with conversation memory, voice↔chat, and Heroku webhook hosting.
- Evolved bot memory from in-memory arrays → MariaDB/PostgreSQL persistence → text-embedding–based history recall for long-context replies.
- Added voice-to-chat and chat-to-voice using Whisper / faster-whisper plus TTS backends; kept Telegram `sendChatAction("typing")` alive during model turns.

## Selected projects

### On-Demand Modular LLM Architecture

- Architected a flexible LLM system with dynamically loaded modules that optimized resource consumption by **50%** vs monolithic models; lightweight router improved response time by **20%** by directing queries to specialized modules.
- Designed pluggable adapters for LLM, STT/TTS, and vector-store providers so modules load on demand without rewriting orchestration.
- Delivered offline-first Persian Assistant ([`project-sorush`](https://github.com/itzreqle/project-sorush)) on FastAPI with health checks and hybrid adapters (HuggingFace/OpenAI/Anthropic/Google LLMs; Whisper STT; TTS backends).

### AI Agent with Dynamic RAG & Multi-Agent System

- Built a dynamic RAG pipeline that improved response accuracy by **35%**, with tools and Elasticsearch vector updates from user feedback.
- Persian assistant / RAG stack on FastAPI + LangChain + LangGraph; hybrid retrieval across Pinecone, Elasticsearch, and Qdrant; Persian-oriented models (Dorna / PersianMind-class); conversational memory.
- Extended [`dynamic-rag-agent`](https://github.com/flowbit-io/dynamic-rag-agent) with index/retrieval/researcher graphs, Ollama embeddings, web/YouTube tooling, Dockerized LangGraph API packaging.
- Designed multi-vector and hybrid retrieval over large conversation/history corpora (relational + vector indexes).

### Other AI / data work

- **Custom Automation Workflows** — n8n automations (Gmail, Linear) reducing manual effort by **15+ hours/week**.
- **Text Embeddings Analyzer** — Cohere/OpenAI/Google embeddings with PCA, K-means, similarity matrices, ARI comparison ([repo](https://github.com/itzreqle/text-embeddings-analyzer)).
- **Podica** — React Native podcast app with emotion-based recommendation engine (**4.8★**, **~40%** engagement lift in first three months).
- **Open-source AI experiments** — Next.js AI chatbot, Python ChatGPT bot, OpenAI API key verifier, VAE image-generation experiment, LangGraph research/business agent demos.

## Skills (AI lens)

- **Orchestration:** LangChain, LangGraph, multi-agent orchestration, tool routing, prompt engineering, agent harnesses, model gateways, MCP, `AGENTS.md` / `SKILL.md`
- **RAG & vectors:** Hybrid RAG (Pinecone + Elasticsearch + Qdrant), multi-vector retrieval, embeddings evaluation
- **Models & inference:** Hugging Face, Ollama, MLX, local inference on Apple Silicon, Persian LLM/RAG (Dorna / PersianMind-class), LLM fine-tuning (supervised & unsupervised), reinforcement learning
- **Speech & media:** OpenAI Whisper / faster-whisper, TTS backends, STT/TTS, voice↔chat, Higgsfield generative media API
- **Data science:** Pandas, NumPy, SciPy, scikit-learn, Jupyter, Matplotlib/Seaborn/Plotly, EDA / statistical analysis
- **APIs:** OpenAI, Anthropic, Telegram Bot API, FastAPI

## Exploring / roadmap *(not claimed as production)*

- Phase-3 agent runtime path (Mastra and Vercel AI SDK)
- Speech-to-speech research direction for the Persian assistant
- Shared agent harnesses / parallel agents for deeper platform DX coupling
- Vendored OpenCode / Cline / Zed positioned for future SSO and inference-gateway integration

## Cross-links

**Roles:** [Cloud / Platform](cloud-platform.md) · [DevOps](devops.md) · [Backend](backend.md) · [Full-Stack](fullstack.md)

**Experience:** [flowbit](../experience/flowbit.md) · [ERP](../experience/enterprise-bpmn-erp.md) · [Soren](../experience/soren-group.md) · [Dabelclick](../experience/dabelclick.md) · [Freelance](../experience/freelance.md)
