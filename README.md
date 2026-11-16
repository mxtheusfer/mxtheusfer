## Matheus Ferracini

**Linux Systems & Infrastructure Administrator** · Rio de Janeiro, Brazil → relocating to Portugal

I run the infrastructure behind a hosting company: 8 production Linux servers, about 225 active customers, and on-call for whatever breaks at 3 a.m.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matheus-ferracini/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:matheusferracini.2016@gmail.com)

---

### About

- Founder of **[RedHosting](https://redhosting.com.br)**, solely responsible for its infrastructure since 2023: **VPS on KVM/VirtFusion**, game servers on **Pterodactyl/Wings**, cPanel hosting and billing on **WHMCS**.
- Background in **computer networking** (technical diploma, FAETEC 2022–2024) and an IT & network support internship at FAETEC.
- I build internal tooling with **AI-assisted development**: I design the system, review the code and ship it to production.
- Looking for **Linux, infrastructure, sysadmin or NOC roles in Portugal**.

### Things I've fixed in production

| Problem | What I did |
|---|---|
| Recurring nginx outages across nodes | Traced them to a typo in an upstream hostname plus transient DNS failures. Fixed both and the outages stopped |
| WHMCS suspending customers by mistake | Found a broken addon injecting a bad SQL query into the automation run and removed it |
| Game-server nodes running out of disk | Quarantined orphaned backups and cleaned up a 115 GB plugin database |
| Compromised customer VPS and containers | Isolated a crypto miner installed through RDP brute force and a Go-based botnet inside a container, then hardened access |
| Failed VM live migrations | Debugged VirtFusion migrations, VNC port conflicts and stale macvtap interfaces |
| Panel and billing server moves | Migrated WHMCS (Apache, PHP 8.1, ionCube, MariaDB) and the VirtFusion control panel to new hosts, and moved game nodes to new SSDs with rsync and integrity checks |

### Projects

| Project | What it does | Stack |
|---|---|---|
| **VIP Platform** | Multi-tenant SaaS where Minecraft server owners run their own store and sell in-game ranks. Subdomain stores, custom domains with DNS verification and automatic SSL, PIX / Mercado Pago / PayPal payments | Node.js, TypeScript, React, Prisma, MySQL, Kotlin plugin |
| **Backup automation** | Daily backups of game nodes to MinIO, and WHMCS database dumps shipped to Google Drive with rclone and cron | Bash, cron, rclone, MinIO |
| **Support ticket bot** | Discord bot that handles RedHosting support tickets and tracks response metrics | Python, py-cord |
| **SSL automation** | Wildcard certificates issued and renewed through Cloudflare DNS-01 | acme.sh, Cloudflare API |

### Tech Stack

**Systems & Virtualization**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![KVM](https://img.shields.io/badge/KVM-333333?style=for-the-badge&logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

**Networking & Web**

![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white)

TCP/IP · DNS · DHCP · VLANs · Firewalls · IPMI

**Hosting Platforms**

Pterodactyl/Wings · VirtFusion · WHMCS · cPanel · Chatwoot

**Development**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

### Currently

- Running RedHosting's infrastructure day to day.
- Studying for my move to Portugal and a networking program there.
- Languages: Portuguese (native), English (B1), Spanish (A2), German (A1).
