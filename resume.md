# ChiCho FOSS  
Los Angeles Metropolitan Area (Westlake Village, CA)  
Email: ch1ch0@duck.com - Phone: 305-970-9255 - GitHub: https://github.com/ch1ch0-foss - LinkedIn: https://www.linkedin.com/in/chicho-foss-42b676165/

***

## Summary

Self-taught **Linux System Administrator / Infrastructure Engineer** designing and operating a self-hosted, Git-centric platform on Fedora Asahi (Apple M1) and ThinkPad T480. Built a production-style homelab with Forgejo (Git), CI/CD, Prometheus/Grafana, Vaultwarden, and local LLM tooling, using Ansible for reproducible infrastructure. Previously owned and ran a barbershop for 10 years, bringing small-business resilience, customer focus, and operational discipline into IT.

***

## Technical Skills

### Operating Systems & Core
- **Linux Distributions**: Fedora, RHEL, Ubuntu, Asahi Linux (ARM)
- **Systemd**: Service management, timers, socket activation
- **SELinux**: Basic configuration and troubleshooting
- **Boot**: Boot process, GRUB, initramfs

### Infrastructure as Code & Automation
- **Ansible**: Roles, playbooks, inventories, idempotent configuration
- **Configuration Management**: Dotfiles automation, reproducible setups
- **GitOps**: Infrastructure defined in code, version controlled

### Version Control & CI/CD
- **Git**: Branching strategies, merging, rebasing, code review
- **Forgejo**: Self-hosted Git service with Actions CI/CD
- **CI/CD Pipelines**: Multi-stage pipelines (lint, syntax-check, docs)
- **Mirroring**: SSH-based push mirrors to GitHub

### Containers & Orchestration
- **Podman**: Rootless containers, docker-compose compatibility
- **Container Security**: Security contexts, capabilities, seccomp
- **nginx**: Reverse proxy, load balancing concepts

### Databases
- **PostgreSQL**: Installation, configuration, user management
- **pgvector**: Vector extension for AI/RAG workloads
- **Backup/Restore**: pg_dump, point-in-time recovery concepts

### Monitoring & Observability
- **Prometheus**: Metrics collection, scrape configs, alerting rules
- **Grafana**: Dashboards, data sources, alerting
- **node_exporter**: System-level metrics (CPU, memory, disk, network)
- **Performance Tools**: htop, btop, iostat, sar, perf

### Security
- **SSH Hardening**: Key-based auth, certificate authorities, config
- **firewalld**: Zone management, rich rules, service definitions
- **Vaultwarden**: Secrets management, backup, restore
- **Network Security**: Tailscale zero-trust VPN concepts

### Networking
- **Tailscale**: Mesh VPN, ACLs, subnet routers
- **DNS**: Basic DNS concepts, local resolution
- **Reverse Proxy**: nginx configuration, TLS termination

### Development Tools & Workflow
- **Editors**: Vim/Neovim with custom configuration
- **Shell**: bash, zsh, tmux multiplexing
- **CLI Tools**: ripgrep, fd, fzf, bat, jq, curlie
- **Productivity**: nb (notebooks), navi (cheatsheets), w3m

### AI/ML Platform (Self-Hosted)
- **DMR**: Docker Model Runner for local LLM inference
- **Models**: Qwen3 8B, 4B, 0.6B (quantized)
- **MCP**: Model Context Protocol for AI integration
- **RAG**: PostgreSQL + pgvector for embeddings
- **OpenCode**: AI-assisted development environment

### Project Management
- **Beads**: Task tracking, epics, dependencies
- **Documentation**: ADRs, runbooks, troubleshooting guides
- **Architecture**: System design, decision records  

***

## Homelab / Portfolio Projects

### srv-m1m Asahi Infrastructure Platform (Homelab, 2025–Present)

**Role**: Production Infrastructure Architect (self-directed)  
**Tech**: Fedora Asahi (ARM64), Ansible, Forgejo, PostgreSQL + pgvector, Prometheus, Grafana, Vaultwarden, DMR, MCP Server, Podman, Tailscale.

**Architecture**: Control-plane / data-plane design with T480 as the Ansible control node managing srv-m1m (Apple M1).

**Services Deployed**:
- **Forgejo** (port 3000): Git server with full CI/CD capabilities
- **PostgreSQL** (port 5432): Database with pgvector for RAG/AI
- **Prometheus** (port 9090): Metrics collection
- **Grafana** (port 3001): Visualization and dashboards
- **Vaultwarden** (port 8222): Secrets/password management
- **DMR** (port 12434): Local AI/LLM with Qwen3 models
- **MCP Server** (port 8082): AI context protocol
- **nginx** (port 80/443): Reverse proxy
- **Syncthing** (port 8384): File synchronization
- **node_exporter** (port 9100): System metrics

**Key Achievements**:
- Designed and implemented **enterprise-style control-plane architecture**
- Deployed **10+ production services** via Ansible (20+ roles)
- Configured **Tailscale zero-trust network** for secure service access
- Built **complete monitoring stack** with Prometheus + Grafana
- Implemented **CI/CD pipelines** with Forgejo Actions
- Deployed **local AI platform** with DMR + MCP for development assistance
- Configured **secrets management** with Vaultwarden

**Key outcomes**: Demonstrated ability to design and run a production-style platform with Git, CI/CD, monitoring, secrets, and AI services on bare metal Linux.

***

### T480 Control Plane Workstation (Homelab, 2025–Present)

**Role**: Linux System Administrator / Platform Engineer (self-directed)  
**Tech**: Fedora, Sway (Wayland), Ansible, Vim/Neovim, OpenCode, DMR, MCP Server, Beads, Syncthing, Tailscale.

**Role**: Acts as the **control plane** that manages srv-m1m via Ansible.

**Workstation Configuration**:
- **OS**: Fedora Linux with Sway window manager
- **Security**: firewalld, SSH hardening, SELinux basics
- **Automation**: Ansible with 20+ roles for infrastructure management
- **AI**: OpenCode + DMR (local AI via Tailscale)
- **Task Tracking**: Beads for infrastructure tasks
- **Development**: Vi-centric environment (vim, tmux, ripgrep, fd, fzf)
- **Sync**: Syncthing with srv-m1m for file synchronization

**Key Achievements**:
- Built **enterprise-style workstation** with full Ansible automation
- Configured **vi-centric development environment** with modern CLI tools
- Integrated **AI-assisted development** with OpenCode + DMR
- Implemented **task management** with Beads (equivalent to GitHub Issues)
- Established **documentation standards** with ADRs and runbooks
- Configured **Tailscale VPN** for secure remote infrastructure access

**Key outcomes**: Proved ability to design and automate a Linux workstation as a formal control plane for infrastructure management.

***

### AI-Assisted Development Platform (In Progress)

**Role**: Platform Engineer (self-directed)  
**Tech**: OpenCode, DMR (Docker Model Runner), MCP Server, PostgreSQL + pgvector, Ansible, Beads.

**Components**:
- **OpenCode**: AI-powered development environment running locally
- **DMR**: Docker Model Runner hosting Qwen3 models (8B, 4B, 0.6B)
- **MCP Server**: Exposes project Markdown as context to AI
- **RAG Pipeline**: PostgreSQL with pgvector for document embeddings

**Key Achievements**:
- Deployed **local AI infrastructure** using DMR on ARM64 (srv-m1m)
- Configured **Ansible roles** for reproducible AI platform deployment
- Built **MCP integration** for project-aware AI responses
- Designed **RAG architecture** for documentation embedding
- Integrated **Beads** for AI-assisted task planning

**Key outcomes**: Demonstrates forward-looking approach to AI-assisted operations while keeping infrastructure self-hosted and under local control.

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
- Stabilize OpenCode + DMR + MCP Phase 1, then begin Phase 2 RAG over official documentation.  

