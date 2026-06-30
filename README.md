<h1 align="center">Hi, I'm Mawuse 👋</h1>
<h3 align="center">Computer Engineer | Cybersecurity Trainee | Network & Software Builder</h3>

<p align="center">
First Class Computer Engineering graduate from Academic City University, Ghana.
Currently a Cybersecurity NSS Trainee at Molaprise, building practical skills across security operations, network automation, and full-stack development.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CCNA-Certified-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Google-Cybersecurity%20Certificate-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Cybersecurity%20%26%20Software%20Engineering-orange?style=flat-square" />
</p>

---

## Cybersecurity Portfolio

A structured, hands-on path covering Linux fundamentals, security theory, CTF problem-solving, SOC monitoring, and network automation. Each stage builds on the last.

**Bandit: Linux Fundamentals & Privilege Escalation**
Completed all 34 levels of OverTheWire Bandit, covering shell navigation, permissions, basic cryptography, and privilege escalation techniques.
📁 Write-up: `overthewire/` in [ctf-writeups](https://github.com/makk-007/ctf-writeups)

**Google Cybersecurity Professional Certificate**
Completed Google's professional certificate covering security frameworks, network defense, incident response, and SIEM fundamentals.

**CyLab Security Academy: General Skills & Forensics**
Solved CTF-style challenges spanning general security skills and digital forensics, using tools like `exiftool`, `binwalk`, `steghide`, and `zsteg`.
📁 Write-up: `picoctf(cylabsecurity)/` in [ctf-writeups](https://github.com/makk-007/ctf-writeups)

**Wazuh SOC Lab**
Deployed a single-node Wazuh SOC environment, building custom decoders, log ingestion pipelines, and threat-hunting workflows for endpoint monitoring.
📁 Repo: [wazuh-soc-lab](https://github.com/makk-007/wazuh-soc-lab)

**Netmiko Network Automation Tool**
Built a Python automation tool using Netmiko to manage network devices in a GNS3 lab, including MikroTik routers, with structured output parsing via TextFSM.
📁 Repo: [netmiko-network-automation-tool](https://github.com/makk-007/netmiko-network-automation-tool)

---

## Software Engineering Projects

Full-stack TypeScript applications built to solve real organizational problems, alongside a systems-level project exploring high-performance infrastructure.

- **Aegis** (private repository, in progress)
A high-performance HTTP reverse proxy and gateway built for routing LLM API traffic. The system splits work across two cooperating planes: a C execution plane handles the hot path (epoll/kqueue event loop, TLS via OpenSSL, HTTP parsing, connection pooling, and SSE streaming passthrough), while a Python control plane handles telemetry ingestion, request trace reconstruction, and latency/throughput/cost metrics. The two planes communicate through a lock-free, single-producer single-consumer ring buffer in POSIX shared memory, allowing the C side to emit telemetry without blocking on Python. Core layers (SHM ring buffer, TLS and event loop wiring, streaming passthrough, and Python-side ingestion) are complete and have been validated with AFL++ fuzzing and Valgrind/MSan memory-safety tooling, which surfaced and fixed real bugs including an HTTP parser buffer overflow and a silent error-suppression bug in the streaming relay. Remaining work covers production hardening: auth/secrets management, rate limiting, circuit breaking, and deployment.

- **Visitor Management System** (private repository, organization project): Digital check-in/check-out system for managing facility visitors.
- **[University Application Dashboard](https://github.com/makk-007/university-application-dashboard)**: Dashboard for managing and tracking university applications.
- **Church Management System** (private repository, organization project): Platform for managing congregation records, attendance, and operations.
- **[Job Application Dashboard](https://github.com/makk-007/job-application-dashboard)**: Tool for tracking and managing job applications end to end.

---

## Skills & Tools

| Category | Tools / Technologies |
|---|---|
| Security & SOC | Wazuh, Wireshark, The Sleuth Kit, steghide, zsteg, exiftool |
| Networking | CCNA, GNS3, MikroTik CHR, Netmiko, TextFSM |
| Programming | Python, TypeScript, React, C, Bash |
| Platforms | OverTheWire, CyLab Security Academy, Google Cybersecurity Certificate |

---

## Connect

📫 Reach me via [LinkedIn](https://www.linkedin.com/in/mawusenam-ackuaku)
