# ChiCho FOSS - Professional Portfolio

> Infrastructure Engineer | Linux System Administrator | Platform Engineer

## Overview

Welcome to my professional infrastructure portfolio. I specialize in enterprise-grade Linux system administration, infrastructure automation, and platform engineering with a focus on building scalable, secure, and maintainable systems.

As a career transitioner into the Linux technology field, I bring enterprise-level thinking and systematic approaches to infrastructure challenges. My work demonstrates practical expertise in modern infrastructure practices, comprehensive documentation, and professional operational standards.

## Career Focus

I am actively seeking opportunities in:

### 🖥️ Linux System Administrator
- System administration and security hardening
- Performance tuning and optimization
- Backup and disaster recovery procedures
- User access management and security compliance

### 🏗️ Infrastructure Engineer  
- Infrastructure as Code with Ansible
- CI/CD pipeline implementation and management
- Container orchestration and microservices
- Network configuration and security

### ⚙️ Platform Engineer
- System monitoring and observability
- Automation and orchestration solutions
- Cross-platform integration and compatibility
- Developer experience and productivity tools

## Portfolio Projects

### 🔧 [T480 Control Plane Workstation](https://github.com/ch1ch0-foss/labs-t480)
**Enterprise-grade Linux workstation management**

The T480 serves as the **control plane** that manages the srv-m1m data plane server:

```
T480 (Control Plane) ──Ansible──► srv-m1m (Data Plane)
     │                                    │
     ├── OpenCode (AI)                   ├── Forgejo
     ├── Beads (Tasks)                   ├── PostgreSQL
     └── Monitoring                       ├── Prometheus
                                           ├── Grafana
                                           ├── Vaultwarden
                                           └── DMR (AI)
```

**Key Demonstrations**:
- Control-plane / data-plane architecture design
- Ansible automation for infrastructure management
- Vi-centric development environment
- Self-hosted AI integration (OpenCode + DMR)
- Security hardening and Tailscale VPN

**Technologies**: Fedora Linux, Sway, Ansible, OpenCode, DMR, MCP, Beads, Tailscale

---

### 🚀 [SRV-M1M Asahi Infrastructure Platform](https://github.com/ch1ch0-foss/labs-srv-m1m)
**High-performance ARM infrastructure platform**

Apple M1 running Fedora Asahi Linux as the data and service hub:

**Services Running**:
| Service | Port | Purpose |
|---------|------|---------|
| Forgejo | 3000 | Git server + CI/CD |
| PostgreSQL | 5432 | Database + pgvector |
| Prometheus | 9090 | Metrics collection |
| Grafana | 3001 | Visualization |
| Vaultwarden | 8222 | Secrets management |
| DMR | 12434 | Local AI/LLM |
| MCP Server | 8082 | AI context protocol |
| nginx | 80/443 | Reverse proxy |
| Syncthing | 8384 | File sync |

**Key Demonstrations**:
- ARM infrastructure on Apple Silicon
- 10+ production services via Ansible
- Tailscale zero-trust networking
- Complete monitoring stack
- Self-hosted AI platform

**Technologies**: Apple M1, Asahi Linux, PostgreSQL, Prometheus, Grafana, Vaultwarden, DMR, Podman, Tailscale

---

### 📚 [ChiCho FOSS](https://github.com/ch1ch0-foss/ch1ch0-foss)
**Open source contributions and projects**

Collection of open source work and community contributions demonstrating:
- Software development practices
- Community collaboration
- Code quality and documentation
- Project management and maintenance

---

## Technical Expertise

### System Administration
- **Linux Distributions**: Fedora, RHEL, Ubuntu, Asahi Linux (ARM)
- **Security**: firewalld, SSH hardening, SELinux, Tailscale VPN
- **Performance**: System optimization, resource monitoring, tuning
- **Backup**: Syncthing, rsync, automated backup strategies

### Infrastructure Automation
- **Ansible**: Roles, playbooks, inventories, idempotent configuration
- **GitOps**: Infrastructure as Code, version controlled deployments
- **CI/CD**: Forgejo Actions, multi-stage pipelines
- **Containers**: Podman (rootless), nginx reverse proxy

### Databases
- **PostgreSQL**: Installation, configuration, user management
- **pgvector**: Vector extension for AI/RAG workloads

### Monitoring & Observability
- **Prometheus**: Metrics collection, scrape configs, alerting
- **Grafana**: Dashboards, data sources, alerting rules
- **node_exporter**: System-level metrics

### Development Tools
- **Editors**: Vim/Neovim with custom configuration
- **Shell**: bash, zsh, tmux
- **CLI**: ripgrep, fd, fzf, bat, jq, navi

### AI/ML Platform (Self-Hosted)
- **DMR**: Docker Model Runner for local LLM
- **Models**: Qwen3 8B, 4B, 0.6B
- **MCP**: Model Context Protocol
- **RAG**: PostgreSQL + pgvector

## Professional Values

### 🎯 **Documentation Excellence**
I believe comprehensive documentation is critical for enterprise environments. Every project includes detailed ADRs, runbooks, and troubleshooting guides.

### 🔒 **Security-First Approach**
Security is integrated throughout the development and deployment process, not an afterthought.

### 🤖 **Automation Mindset**
Manual processes are opportunities for automation. I build systems that are repeatable, scalable, and maintainable.

### 📈 **Continuous Learning**
Technology evolves constantly. I stay current with emerging trends while maintaining strong fundamentals.

## Professional Background

### Career Transition Story
After successful experience as a Barber, I'm making a deliberate transition into Linux infrastructure engineering. My approach combines enterprise thinking with hands-on technical skills and modern infrastructure practices.

### Education & Training
- **Self-Directed Learning**: Comprehensive study of Linux system administration
- **Practical Implementation**: Real-world projects demonstrating enterprise capabilities
- **Community Engagement**: Active participation in open source communities
- **Continuous Improvement**: Ongoing skill development and certification planning

## Projects Overview

| Project | Focus | Key Demonstrations |
|---------|-------|-------------------|
| T480 Workstation | System Administration | Workstation hardening, automation, monitoring |
| SRV-M1M Platform | Infrastructure Engineering | ARM deployment, services, security |
| ChiCho FOSS | Open Source | Software development, community work |

## Contact & Professional Presence

### 📧 **Professional Contact**
- **Email**: ch1ch0@duck.com 
- **Location**: Thousand Oaks, CA - Available for remote  
- **Availability**: Searching 

### 🔗 **Online Presence**
- **GitHub**: [github.com/ch1ch0-foss](https://github.com/ch1ch0-foss)
- **LinkedIn**: https://www.linkedin.com/in/chicho-foss-42b676165/
- **Portfolio Website**: [www.ch1ch0-foss.me](https://www.ch1ch0-foss.me)

### 📋 **Resume**

View my detailed resume in the [root of this repository](resume.md).

## Why Hire Me

### 🏢 **Enterprise Mindset**
I understand that infrastructure decisions impact business operations and bring enterprise-level thinking to every technical solution.

### 📚 **Documentation Expert**
My projects demonstrate exceptional documentation practices that exceed industry standards, ensuring knowledge transfer and operational excellence.

### 🔧 **Hands-On Experience**
Every skill demonstrated in this portfolio comes from practical implementation, not just theory or tutorials.

### 🚀 **Future-Ready**
I work with emerging technologies (ARM infrastructure, local AI services) while maintaining strong foundational knowledge.

---

*This portfolio represents my commitment to excellence in infrastructure engineering and my passion for building robust, scalable systems. I'm excited to bring my skills and dedication to a team that values quality, documentation, and continuous improvement.*

---

*"Building the infrastructure that powers tomorrow's applications, today."*
