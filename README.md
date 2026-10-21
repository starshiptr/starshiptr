# Isaac Louis

**I build and run the infrastructure other people depend on, and the AI automation on top of it, behind gates that verify its work.**

Infrastructure Engineer at Astrophel Aerospace, a 15 engineer aerospace startup, where I own the network, the servers, the identity stack and the monitoring end to end. B.Tech. I also design and deliver networks as a paid independent consultant.

### Latest

**[redteam-action](https://github.com/starshiptr/redteam-action)**: a GitHub Action where Claude attacks every pull request, but a bug only counts if a test proves it. Each proof runs before and after the PR in a sandbox with no network and no secrets. On a public eval set of [8 pull requests](https://github.com/starshiptr/redteam-eval/pulls), each one reintroducing a real bug: **8/8 caught, 0 false alarms, about $0.02 per PR.**

### Selected work

| Project | What it is | Stack |
|---|---|---|
| [redteam-action](https://github.com/starshiptr/redteam-action) | AI code review that only reports bugs it can prove with an executed test. Sandboxed, escape tested in CI | Python · GitHub Actions · Linux namespaces · Claude API |
| [office-it-infrastructure](https://github.com/starshiptr/Office-IT-Infrastructure) | Production IT environment for an aerospace startup: bare metal servers, the office network, AD identity and multi user compute. Cut hardware spend ~40% | Windows Server 2022 · Active Directory · RDS · Cloudflare Zero Trust |
| [school-network-deployment](https://github.com/starshiptr/school-network-deployment) | Solo design and delivery of a segmented, monitored school campus network. Paid engagement, handed over with a runbook | Proxmox VE · pfSense · VLANs · Graylog · Zabbix |
| [personal-dashboard](https://github.com/starshiptr/personal-dashboard) | Self hosted spending, fitness and task tracker on AWS EC2 with zero inbound ports, reachable only over Tailscale. CI on every push | Python · Streamlit · SQLite · AWS EC2 · GitHub Actions |
| [astro-planner-pipeline](https://github.com/starshiptr/astro-planner-pipeline) | Voice notes to Microsoft Planner tasks with a human approval gate. A case study in retiring your own app | Python · Microsoft Graph API · systemd |
| [nasa-ntrs-mcp](https://github.com/starshiptr/nasa-ntrs-mcp) | MCP server that lets an AI assistant search and read NASA technical reports in plain English | Python · MCP |


### Currently building

AWS Cloud Practitioner (CLF-C02), then Terraform and AWS Solutions Architect (SAA-C03). A DNA data storage pipeline with error correction, built in public at [dna-storage](https://github.com/starshiptr/dna-storage).

### Stack

![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white) ![pfSense](https://img.shields.io/badge/pfSense-212121?style=flat-square&logo=pfsense&logoColor=white) ![Windows Server](https://img.shields.io/badge/Windows%20Server-0078D6?style=flat-square&logo=windows&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Claude](https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=anthropic&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare%20Zero%20Trust-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

Also: Hyper-V, Active Directory, VLANs and 802.1Q, Tailscale, MCP servers, Uptime Kuma, Bash.

### Reach me

[LinkedIn](https://www.linkedin.com/in/isaac-louis) · isaaclouis06@gmail.com
