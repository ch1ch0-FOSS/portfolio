# ChiCho FOSS  
Los Angeles Metropolitan Area (Westlake Village, CA)  
Email: ch1ch0@duck.com - Phone: 305-970-9255 - GitHub: https://github.com/ch1ch0-FOSS - Forgejo: [srv-m1m URL] - LinkedIn: https://www.linkedin.com/in/chicho-foss-42b676165/

***

## Summary

Self-taught **Linux System Administrator / Infrastructure Engineer** designing and operating a self-hosted, Git-centric platform on Fedora Asahi (Apple M1) and ThinkPad T480. Built a production-style homelab with Forgejo (Git), CI/CD, Prometheus/Grafana, Vaultwarden, and local LLM tooling, using Ansible for reproducible infrastructure. Previously owned and ran a barbershop for 10 years, bringing small-business resilience, customer focus, and operational discipline into IT.

***

## Technical Skills

- **Linux / OS**: Fedora, RHEL-family, systemd, SELinux basics, SSH hardening, user and service management.  
- **Infrastructure as Code**: Ansible (roles, playbooks, inventories), idempotent server configuration, dotfiles automation.  
- **Git & Platforms**: Git (branching, PRs, code review), Forgejo server administration, SSH-based mirroring to GitHub, Forgejo Actions.  
- **CI/CD & Automation**: Forgejo Actions pipelines (lint, syntax-check, docs), pre-commit hooks, local-first build/test workflows.  
- **Containers**: Podman (rootless), containerized Nginx, reverse proxying for internal services.  
- **Monitoring & Observability**: Prometheus, node_exporter, Grafana dashboards, perf-tools (perf, strace, iostat, sar).  
- **Security & Secrets**: SSH hardening, basic firewalling (firewalld), Vaultwarden deployment planning, password management concepts.  
- **Networking**: Tailscale mesh VPN, basic DNS, service exposure over private network only.  
- **Tooling & Workflow**: vi/vim, tmux, ripgrep, fd, fzf, bat, jq, nb (notebooks), navi (cheatsheets).  
- **AI/LLM Platform (in progress)**: Ollama on ARM64 (T480 + srv-m1m), OpenCode, Beads task management, early MCP integration.  

***

## Homelab / Portfolio Projects

### srv-m1m Asahi Infrastructure Platform (Homelab, 2025–Present)

**Role**: Production Infrastructure Architect (self-directed)  
**Tech**: Fedora Asahi (ARM64), Fedora 43 (x86_64), Ansible, Forgejo, Prometheus, Grafana, Vaultwarden, Podman, Tailscale, PostgreSQL.

- Designed a **control-plane / data-plane** architecture with T480 as the control node and srv-m1m (Apple M1) as the service and data hub, managed entirely via Ansible.  
- Deployed **Forgejo** as the central Git service, configured SSH access, and implemented a secure push mirror to GitHub using deploy keys (no PATs) to publish a professional portfolio.  
- Implemented **CI/CD** with Forgejo Actions, including multi-stage pipelines (linting, Ansible syntax-check, documentation checks) and a dedicated runner on srv-m1m.  
- Built an initial **monitoring stack** with Prometheus, node_exporter, and Grafana dashboards to observe host metrics and homelab services, including early plans for Ollama and RAG observability.  
- Containerized an **Nginx web server** with Podman (rootless) as a reverse proxy for internal apps and future Forgejo Pages, aligning with Fedora container practices.  
- Planned and began deployment of **Vaultwarden** for secrets management, with backup and DR considerations documented for srv-m1m.  

**Key outcomes**: Demonstrated ability to design and run a small but realistic internal platform with Git, CI/CD, monitoring, and secrets on bare metal Linux.

***

### ansible-workstation & T480 Control Plane (Homelab, 2025–Present)

**Role**: Linux System Administrator / Platform Engineer (self-directed)  
**Tech**: Fedora, Ansible, vi/vim, tmux, Forgejo, Syncthing, nb, navi, Beads.

- Built an **enterprise-style workstation role** in Ansible to configure the T480: core packages, SELinux, SSH hardening, vi-centric tooling, and terminal environment (foot, wl-clipboard).  
- Designed a **vi-centric development environment** with vim, tmux, and modern CLI tools (ripgrep, fd, fzf, bat, jq), plus nb and w3m/vimb for Markdown docs and browsing.  
- Implemented **dotfiles management** via Ansible (planned and partially executed) to replace ad-hoc tooling, making the T480 environment reproducible and easy to restore.  
- Integrated **Syncthing** (planned) and Tailscale so that key directories (docs, labs, selected nb notes) can sync between T480 and srv-m1m under a local-first model.  
- Standardized work tracking with **Beads (`bd`)** as the canonical task system, and used Markdown ADRs and runbooks to capture design decisions and operational procedures.  

**Key outcomes**: Proved ability to design and automate a consistent Linux workstation setup and to treat a laptop as a formal infrastructure control plane.

***

### OpenCode + Ollama + MCP Platform (Phase 1 – In Progress)

**Role**: Platform Engineer (self-directed)  
**Tech**: OpenCode, Ollama (ARM64), Ansible, Beads, MCP.

- Defined and documented an epic to run **OpenCode** on the T480 against **Ollama** locally and on srv-m1m, using Ansible roles and systemd overrides to tune context length and resource usage.  
- Planned and started integration of **Beads** as the source of truth for tasks, including conventions for epics, tasks, dependencies, and commit message standards.  
- Designed a **minimal MCP server** concept to expose project-local Markdown (ADRs, runbooks, infra docs) as structured context to OpenCode, separate from any future RAG over official docs.  
- Outlined a **Phase 2 RAG architecture** to index vendor documentation (RHEL, PostgreSQL, Prometheus, Forgejo) on srv-m1m and expose it through a self-hosted RAG API, restricted via Tailscale.  

**Key outcomes**: Shows forward-looking work on AI-assisted operations while keeping infrastructure self-hosted, observable, and under local control.

***

## Professional Experience (Pre-IT)

### Owner / Licensed Barber – Self-Employed, Thousand Oaks, CA  
2017 – Present

- Owned and operated a local barbershop, managing scheduling, customer relationships, and cash flow while maintaining consistent service quality.  
- Trained and mentored junior barbers, standardizing procedures and resolving issues quickly under pressure.  
- Adapted to changing customer needs and tools, building a loyal client base over 8+ years.  

**Transferable strengths**: Customer communication, reliability, time management, learning new tools quickly, and making independent decisions in an operational environment.

***

## Education

- **Self-taught Linux & Infrastructure Engineering** – 2025–Present  
  Focus: Fedora/RHEL administration, Ansible, Git, CI/CD, monitoring, containers, and self-hosted services.  

- Additional learning through documentation, community resources, and hands-on homelab work.  

***

## Selected Roadmap Highlights (Ongoing Work)

- Complete deployment of Prometheus/Grafana for full homelab observability.  
- Migrate dotfiles fully to Ansible, including host-specific overrides.  
- Finish Vaultwarden deployment and backup strategy on srv-m1m.  
- Stabilize OpenCode + Ollama + MCP Phase 1, then begin Phase 2 RAG over official documentation.  

