# DevOps & Infrastructure

CI/CD, containers, Kubernetes scaffolds, self-hosted GitLab, observability, and Linux operations.

[Email](mailto:Kingreqle@gmail.com) · [GitHub](https://github.com/itzreqle) · [flowbit](https://github.com/flowbit-io) · [Profile README](../README.md)

## Summary

DevOps-leaning platform engineer who builds and operates delivery pipelines, container platforms, self-hosted Git forges, and observability stacks that keep developer platforms and enterprise apps shipping. Experience spans GitHub Actions, GitLab CI, Docker/Kubernetes, Traefik, Loki/Prometheus/Grafana, WireGuard, multi-distro Linux, and constrained-network deployments.

## Relevant experience

### Founder & CTO · [flowbit](../experience/flowbit.md) · Remote · 2024 – Present

- Operated **self-hosted GitLab CE with GitLab Runner** (Docker) for private repositories, HTTPS/SSH access, and team CI/CD workflows supporting platform development.
- Led DevOps initiatives for advanced CI/CD pipelines and Kubernetes-based microservices, cutting deployment times by **~40%** and improving system scalability.
- Delivered multi-arch Docker images (`linux/arm64` and `linux/amd64`) for ARM Mac → x86 VPS deployments; practiced resource-conscious container runtimes (Colima / minimal Docker).
- Connected distributed development infrastructure with WireGuard-based VPN patterns so local, VPS, and self-hosted services operate as one environment.
- Established platform ops foundations: Postgres, Redis, MinIO, Traefik, Loki/Prometheus/Grafana overlays; Docker Compose and Kubernetes scaffolds in the monorepo.
- Provisioned and operated multi-distro Linux servers and desktops (Ubuntu Server, Rocky Linux, Alpine; Arch-family including Omarchy; BlackArch / Kali for security tooling; GNOME and Hyprland Wayland environments) from bare VPS through application runtime.
- Delivered apps behind Cloudflare (DDoS / bot mitigation, Cloudflare Pages) and PaaS hosts including Vercel (deploy, Analytics, Firewall), Render, DigitalOcean, and Heroku webhooks.
- Used Google Cloud Compute, IAM, and Maps/GPS APIs for backends and secured development environments; applied Ansible alongside GitHub/GitLab CI for remote deploys (AWS familiarity without production AWS tenure).
- Built agentic CI/CD workflows: GitHub Actions calling the Gemini API for branch/PR conversation summaries; Cursor and Claude agents for PR/commit/task analysis; repo `AGENTS.md` / `SKILL.md`, MCP tool servers, sub-agents, and sandboxed harnesses with human review so secrets never enter models.
- Operated the infra monorepo CMS Compose services and delegated agentic app init/dev/build from the platform root while bumping dashboard and marketing submodules for security and feature delivery.

### Full-Stack / Platform Engineer · [Enterprise BPMN ERP](../experience/enterprise-bpmn-erp.md) · Remote · 2025 – 2026 *(concurrent)*

- Delivered Docker-based packaging and CI/CD (GitHub Actions / GitLab CI), including constrained-network and offline image-transfer deployment paths.
- Implemented production deploy automation with GitHub Actions (SSH and VPN-assisted server rollout) and documented Docker Compose local stacks for MongoDB, Redis, and Elasticsearch.
- Led brownfield modernization and security assessment: auth hardening, connector isolation, phased upgrade roadmap, and characterization of scale targets (queues, real-time auth, observability).

### Software Developer · [Soren Group](../experience/soren-group.md) · Tehran · 2022 – 2024

- Maintained **99.9%** server uptime by monitoring server health and performance using cPanel and related administration tools.
- Boosted application performance by **30%** by analyzing performance data, identifying bottlenecks, and implementing targeted optimizations.

### Freelance · [Freelance](../experience/freelance.md) · Remote · 2018 – Present

- Hosted always-on Telegram bots on Heroku (HTTPS webhooks / web dynos) and monitored health with Grafana Loki and Grafana dashboards.
- Built terminal and TUI tooling (downloaders, exporters, CLI shortcuts, automation scripts) that accelerated bot development and day-to-day engineering workflows.

## Selected projects

- **LKRG Systemd Automation** — systemd units and rebuild scripts to install/update/recompile Linux Kernel Runtime Guard when kernel headers change on Debian/RHEL-class systems.
- **FMSS** — Jenkins CI/CD with Docker, Kubernetes/Kustomize overlays (dev/staging/prod), Airbyte data-integration submodule.
- **Edge Hosting and Observability Stack** — Cloudflare + Vercel/Render/DO/Heroku; Loki/Grafana with AI-assisted deploy summaries and structured release notes for Python, JavaScript, Ruby, and Go services.
- **Open-Source ops tooling** — GitHub repository downloader, network information viewers (Python and shell), Kali Linux penetration-testing documentation guide for personal/ops reference.

## Skills (DevOps lens)

- **CI/CD:** Git, Jenkins, GitHub Actions, GitLab CI, self-hosted GitLab CE + Runner, Ansible
- **Containers & orchestration:** Docker, Docker Compose, multi-arch Docker, Colima, Kubernetes, Kustomize overlays, GitOps path
- **Networking & edge:** NGINX, Traefik, WireGuard, Cloudflare (DDoS / Bot Fight / Pages)
- **Observability:** Loki, Prometheus, Grafana
- **Hosts:** Heroku, Vercel, Render, DigitalOcean, Google Cloud (Compute, IAM, Maps), Azure, AWS (familiarity)
- **Linux:** Ubuntu / Ubuntu Server / CentOS / Rocky / Alpine / Arch-family / Omarchy / BlackArch / Kali; GNOME, Hyprland
- **Security tooling:** SSL/TLS, OAuth/JWT, CodeQL, Bandit, LKRG, reverse-engineering analysis (re-implementation)
- **Monorepos:** pnpm / Bun monorepos, git submodules, uv, pipx

## Exploring / roadmap *(not claimed as production)*

- Deeper Kubernetes scheduling, GitOps rollout, and multi-region HA for the flowbit data plane
- FMSS deployment overlays prepared for GitOps-style rollout

## Cross-links

**Roles:** [Cloud / Platform](cloud-platform.md) · [AI](ai.md) · [Backend](backend.md) · [Full-Stack](fullstack.md)

**Experience:** [flowbit](../experience/flowbit.md) · [ERP](../experience/enterprise-bpmn-erp.md) · [Soren](../experience/soren-group.md) · [Dabelclick](../experience/dabelclick.md) · [Freelance](../experience/freelance.md)
