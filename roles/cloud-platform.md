# Cloud / Platform Engineer

Multi-tenant developer cloud, control plane / data plane, and PaaS infrastructure.

[Email](mailto:Kingreqle@gmail.com) · [GitHub](https://github.com/itzreqle) · [flowbit](https://github.com/flowbit-io) · [Profile README](../README.md)

## Summary

Cloud / Platform Engineer and Founder & CTO of **flowbit**, designing and operating a multi-tenant Developer Cloud Platform end to end: control-plane APIs, replaceable infrastructure providers, deployments, edge runtimes, secrets, billing, and observability. Concurrent production NestJS/Next.js enterprise BPMN ERP delivery under NDA. Primary stack: TypeScript, NestJS, Next.js, Docker/Kubernetes, OpenAPI-first APIs.

## Relevant experience

### Founder & CTO · [flowbit](../experience/flowbit.md) · Remote · 2024 – Present

#### Platform architecture

- Architected a multi-tenant Developer Cloud Platform control plane (NestJS, OpenAPI, Drizzle/PostgreSQL, Next.js dashboard) covering authentication, organizations and projects, dual-rail billing (Stripe and Zarinpal), object storage, multi-engine managed databases, secrets vault, Docker deployments with GitHub App builds, cloud shell (WebSocket PTY), workerd-based Edge Functions, unified observability logs, and custom domains.
- Designed OpenAPI-first API contracts and replaceable infrastructure providers (Docker, MinIO, workerd, Traefik, Loki, and related adapters) so the product API stays stable while the data plane evolves.
- Built and operated a pnpm + git-submodule monorepo spanning the NestJS control-plane API, Next.js dashboard, CMS-backed marketing site and engineering blog, Docker Compose / Kubernetes scaffolds, and an agentic DX lane of vendored private forks.
- Authored a large OpenAPI v1 contract and NestJS modules delivered as vertical slices (OpenAPI → API → dashboard → Compose/Kubernetes stubs), enforcing API-over-OS architecture and replaceable providers.
- Framed the platform around a developer UI → orchestration/control plane → Kubernetes/GitOps → workloads model.

#### Hard infrastructure systems

- Built Docker deployments with GitHub App build pipelines, WebSocket PTY cloud shell Dev Workspaces, and Workers-class Edge Functions (Monaco editor, version activate/rollback).
- Shipped multi-engine managed databases (PostgreSQL, MySQL, MariaDB, Redis, MongoDB, ClickHouse), sealed secrets vault, MinIO object storage, and Traefik custom domains.
- Hardened the Next.js control-plane dashboard against scanner probes, added live workspace overview analytics and logs deep links, and gated public sign-up / GitHub auth when registration is disabled.

#### Operations & reliability

- Operated self-hosted GitLab CE with GitLab Runner (Docker) for private repositories, HTTPS/SSH access, and team CI/CD.
- Established local and platform ops foundations (Postgres, Redis, MinIO, Traefik, Loki/Prometheus/Grafana overlays).
- Led CI/CD and Kubernetes-based microservice delivery, cutting deployment times by **~40%**.
- Delivered multi-arch Docker images (`linux/arm64` and `linux/amd64`) and WireGuard-linked local/VPS environments.
- Founded the company and acquired **10+** new clients in the first six months through web, mobile, and automation engagements.

### Full-Stack / Platform Engineer · [Enterprise BPMN ERP](../experience/enterprise-bpmn-erp.md) · Remote · 2025 – 2026 *(concurrent)*

- Delivered production NestJS/Next.js BPMN ERP for workflow, finance, HR, and operations on MongoDB, Redis, Elasticsearch, Socket.IO, and Bull queues.
- Built BPMN task UIs, dynamic forms, process-definition tooling, and role-based task routing.
- Delivered Docker packaging and CI/CD (GitHub Actions / GitLab CI), including constrained-network and offline image-transfer paths; led brownfield auth hardening and connector isolation.

## Selected projects

- **flowbit Developer Cloud** — end-to-end PaaS control plane + dashboard (see [flowbit experience](../experience/flowbit.md)).
- **FMSS** — microservice finance platform with Next.js, Node, .NET auth, PostgreSQL + ClickHouse, Jenkins, Kubernetes/Kustomize overlays, Airbyte.
- **Edge Hosting & Observability** — Cloudflare, Vercel, Render, DigitalOcean, Heroku with Loki/Grafana and CI release notes.

## Skills (platform lens)

- **Architecture:** Control plane / data plane, multi-tenant SaaS, replaceable provider adapters, API-over-OS, microservices, BPMN workflow engines
- **Backend:** NestJS, Node.js, TypeScript, OpenAPI-first design, Drizzle ORM, Better Auth, REST, WebSockets
- **Infra:** Docker, Kubernetes, Traefik, MinIO/S3, workerd / Edge Functions, GitLab CE + Runner, GitHub Actions
- **Data:** PostgreSQL, MySQL/MariaDB, MongoDB, Redis, ClickHouse, Elasticsearch
- **Observability:** Loki, Prometheus, Grafana

## Exploring / roadmap *(not claimed as production)*

- Data plane evolution toward deeper Kubernetes scheduling, GitOps, and multi-region HA
- Polyglot edge/agent runtimes (Rust, Go, WebAssembly, Bun, Deno)
- Vendored OpenCode / Cline / Zed surfaces positioned for later SSO and AI-gateway coupling
- AIaaS Phase-3 agent runtime path (Mastra / Vercel AI SDK) and application marketplace direction

## Cross-links

**Roles:** [DevOps](devops.md) · [AI](ai.md) · [Backend](backend.md) · [Full-Stack](fullstack.md)

**Experience:** [flowbit](../experience/flowbit.md) · [ERP](../experience/enterprise-bpmn-erp.md) · [Soren](../experience/soren-group.md) · [Dabelclick](../experience/dabelclick.md) · [Freelance](../experience/freelance.md)
