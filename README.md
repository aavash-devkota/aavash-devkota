<p align="center">
  <img src="https://img.shields.io/badge/System%20Engineer-●-00e5ff?style=for-the-badge&labelColor=0b1020" />
  <img src="https://img.shields.io/badge/Security%20Enthusiast-●-7c3aed?style=for-the-badge&labelColor=0b1020" />
</p>

<h1 align="center">Aavash Devkota</h1>
<p align="center"><i>System Engineer @ Infrasoft Solutions · Security Enthusiast · Building CVEGuard & DomainWatch</i></p>

<p align="center">
  <a href="mailto:devkotaaavash@gmail.com">email</a> ·
  <a href="https://linkedin.com/in/aavash-devkota">LinkedIn</a> ·
  <a href="https://github.com/aavash-devkota">GitHub</a>
</p>

---

## 🎓 Background

- **B.Sc. CSIT, Tribhuvan University** — 81.07% Distinction, full-tuition merit scholarship
- **PCNSP** (Palo Alto) · **ISC² CC** · **CCNA** (Routing & Switching)

## 🔬 Interests

Vulnerability analysis of complex software systems; supply-chain exposure assessment; domain & email security; infrastructure monitoring.

## 📦 Projects

### 🛡️ CVEGuard — Centralized Vulnerability Management
Supply-chain vulnerability analysis platform (solo final-year project).

- **Stack:** Go · PHP (Laravel 11) · MySQL · OSV/GHSA format
- **Scale:** ~430 MB upstream advisory DB → 7,040 npm vulnerabilities / 3,136 packages seeded in under a minute
- Three-component system: Go CLI lockfile scanner, Go GHSA seeder, Laravel server with semantic-version range matching

| Component | Stack | What it does |
|---|---|---|
| [cveguard-server](https://github.com/aavash-devkota/cveguard-server) | Laravel / PHP | Web UI + API |
| [cveguard-client](https://github.com/aavash-devkota/cveguard-client) | Go | package-lock scanner CLI |
| [cveguard-vulnerabilities-seeder](https://github.com/aavash-devkota/cveguard-vulnerabilities-seeder) | Go | CVE data seeder |

> 📄 Project report: https://aavash-devkota.github.io/cveguard-server/project-report/

### 🔭 DomainWatch — Domain Intelligence & Monitoring
UptimeRobot-for-domains: availability, price, expiration, DNS and security monitoring.
CLI + FastAPI + web dashboard + Prometheus metrics + Docker.

- [DomainWatch](https://github.com/aavash-devkota/DomainWatch) · Docs: https://aavash-devkota.github.io/DomainWatch/

## 🧰 Skills

- **Languages:** C, C++, Python, Bash, Go, PHP, SQL
- **Systems:** Linux, Windows Server, VMware ESXi, Proxmox, Docker, SAN/NAS
- **Networking:** Cisco/Juniper/Palo Alto/Fortinet/Sophos/Ruijie/MikroTik, VLANs, VPN, SD-WAN, firewall policy
- **Security:** SIEM/SOC (Wazuh, Splunk, LogRhythm), Nessus, Burp Suite, Nmap, Wireshark, vulnerability management

---

<p align="center">
  <img src="https://img.shields.io/badge/Docs-CVEGuard-a371f7?style=flat-square" />
  <img src="https://img.shields.io/badge/Docs-DomainWatch-1f6feb?style=flat-square" />
</p>
