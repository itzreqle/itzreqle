# flowbit — Founder & CTO

Remote · 2024 – Present  
Company: Flowbit (branded **flowbit** on this profile)

[Email](mailto:Kingreqle@gmail.com) · [GitHub](https://github.com/itzreqle) · [flowbit org](https://github.com/flowbit-io) · [Profile README](../README.md)

## Summary

Founded and lead engineering for a multi-tenant Developer Cloud Platform: NestJS/OpenAPI control plane, Next.js dashboard, replaceable infrastructure providers, self-hosted GitLab, and AI/agentic DX lanes. Acquired **10+** clients in the first six months through web, mobile, and automation engagements.

## Platform architecture

- Architected a multi-tenant **Developer Cloud Platform** control plane (NestJS, OpenAPI, Drizzle/PostgreSQL, Next.js dashboard) covering authentication, organizations and projects, dual-rail billing (Stripe and Zarinpal), object storage, multi-engine managed databases, secrets vault, Docker deployments with GitHub App builds, cloud shell (WebSocket PTY), workerd-based Edge Functions, unified observability logs, and custom domains.
- Designed OpenAPI-first API contracts and replaceable infrastructure providers (Docker, MinIO, workerd, Traefik, Loki, and related adapters) so the product API stays stable while the data plane evolves toward Kubernetes and GitOps.
- Built and operated a pnpm + git-submodule monorepo spanning the NestJS control-plane API, Next.js dashboard, CMS-backed marketing site and engineering blog, Docker Compose / Kubernetes scaffolds, and an agentic DX lane of vendored private forks.
- Authored a large OpenAPI v1 contract and NestJS modules delivered as vertical slices (OpenAPI → API → dashboard → Compose/Kubernetes stubs), enforcing API-over-OS architecture and replaceable providers.
- Designed and shipped end-to-end PaaS surfaces: multi-tenant auth, org/project model, billing, MinIO object storage, multi-engine managed databases (PostgreSQL, MySQL, MariaDB, Redis, MongoDB, ClickHouse), sealed secrets vault, Docker deployments and GitHub App build pipelines, cloud shell Dev Workspaces, Workers-class Edge Functions (Monaco editor, version activate/rollback), unified log viewer, and Traefik custom domains.
- Built a headless marketing content plane separate from the NestJS control-plane database: typed Strapi 5 contracts (Pages, Products, Solutions, Articles; `en`/`fa`), multi-locale product/solution pages, draft preview and ISR revalidation, editorial blog with collections, tags, and safe embeds.
- Framed the platform around a developer UI → orchestration/control plane → Kubernetes/GitOps → workloads model.
- Hardened the Next.js control-plane dashboard against scanner probes; shipped live workspace overview analytics with deep links into unified observability logs; gated public sign-up / GitHub auth when registration is disabled.
- Directed product management using Jira and Linear, streamlining development cycles and improving time-to-market for new features by **~30%**.

## Hard infrastructure & operations

- Operated **self-hosted GitLab CE with GitLab Runner** (Docker) for private repositories, HTTPS/SSH access, and team CI/CD.
- Led DevOps initiatives for advanced CI/CD pipelines and Kubernetes-based microservices, cutting deployment times by **~40%**.
- Delivered multi-arch Docker images (`linux/arm64` and `linux/amd64`) for ARM Mac to x86 VPS deployments; practiced resource-conscious container runtimes (Colima / minimal Docker).
- Connected distributed development infrastructure with WireGuard-based VPN patterns so local, VPS, and self-hosted services operate as one coherent environment.
- Established local and platform ops foundations (Postgres, Redis, MinIO, Traefik, Loki/Prometheus/Grafana overlays).
- Provisioned and operated multi-distro Linux servers and desktops (Ubuntu Server, Rocky Linux, Alpine; Arch-family including Omarchy; BlackArch / Kali for security tooling; GNOME and Hyprland) from bare VPS through application runtime.
- Delivered apps behind Cloudflare (DDoS / bot mitigation, Cloudflare Pages) and PaaS hosts including Vercel (deploy, Analytics, Firewall), Render, DigitalOcean, and Heroku webhooks.
- Used Google Cloud Compute, IAM, and Maps/GPS APIs for application backends and secured development environments; applied Ansible alongside GitHub/GitLab CI for remote deploys (AWS familiarity without production AWS tenure).
- Operated the infra monorepo CMS Compose services and delegated agentic app init/dev/build from the platform root while bumping dashboard and marketing submodules for security and feature delivery.

## AI / agentic systems

- Architected modular LLMs that reduced inference costs by **~25%** and intelligent agents that automated over **100 hours** of manual work per month.
- Operated local AI inference (Ollama, MLX) on Apple Silicon, applying model memory-versus-disk-size constraints to inform AIaaS product and gateway design.
- Built agentic CI/CD workflows: GitHub Actions calling the Gemini API for branch/PR conversation summaries; Cursor and Claude agents for PR/commit/task analysis; repo `AGENTS.md` / `SKILL.md`, MCP tool servers, sub-agents, and sandboxed harnesses with human review so secrets never enter models.
- Integrated multi-provider AI surfaces (OpenAI, Anthropic, Hugging Face Hub/Inference, Higgsfield generative media API) and offline STT/TTS stacks (OpenAI Whisper / faster-whisper and related speech models) for human-like voice experiences on dedicated servers.
- Advanced agentic developer experience by integrating vendored coding-agent surfaces (Zed, OpenCode, Cline) and exploring shared agent harnesses, parallel agents, and model routing for platform DX.

## Exploring / roadmap *(not claimed as production)*

- Vendored private forks of **OpenCode** (Bun terminal/web/desktop), **Cline** (VS Code extension/CLI/SDK), and **Zed** (Rust IDE) into the monorepo — standalone today, positioned for later platform SSO and AI-gateway coupling.
- AIaaS knowledge-base / RAG configuration UX, guardrails, and a Phase-3 agent runtime path (Mastra and Vercel AI SDK).
- Polyglot systems work targeting Rust, Go, WebAssembly, Bun, and Deno for edge and agent workloads.
- Clear roadmap to Kubernetes scheduling, GitOps, multi-region HA, application marketplace, and deeper observability surfaces.

## Related projects under flowbit

- Podica (`podica-mobile`, `podica-web`) — AI-powered podcast application
- `dynamic-rag-agent` — LangGraph hybrid RAG research agent
- FMSS — Financial Management Service System (scaffolded)
- Smart — headless commerce / WordPress content platform

## Cross-links

**Roles:** [Cloud / Platform](../roles/cloud-platform.md) · [DevOps](../roles/devops.md) · [AI](../roles/ai.md) · [Backend](../roles/backend.md) · [Full-Stack](../roles/fullstack.md)

**Other experience:** [ERP](enterprise-bpmn-erp.md) · [Soren](soren-group.md) · [Dabelclick](dabelclick.md) · [Freelance](freelance.md)
