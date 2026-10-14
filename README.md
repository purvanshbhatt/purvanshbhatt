# Purvansh Bhatt
### **Detection & Response Engineer | Agentic SOC & Cloud IR | Attacker Mindset**
New York, NY • [Website & Portfolio](https://purvanshbhatt.github.io) • [LinkedIn](https://linkedin.com/in/purvanshbhatt) • [Medium](https://medium.com/@purvansh95b) • [Email](mailto:purvansh95b@gmail.com)

> *"Security is a core software engineering problem, not a compliance checklist. Decisiveness. Simplicity. Job's Not Finished."*

[![TryHackMe Top 5%](https://img.shields.io/badge/TryHackMe-Top%205%25%20Global-teal?style=flat-square&logo=tryhackme)](https://tryhackme.com/p/purvansh95)
[![Hack The Box Level 4](https://img.shields.io/badge/HackTheBox-Level%204%20Operator-green?style=flat-square&logo=hackthebox)](https://profile.hackthebox.com/profile/019c4091-8fa1-712f-ad9f-b84b4f221dd2)
[![Google Cloud Innovator](https://img.shields.io/badge/Google%20Cloud-Innovator%202026-blue?style=flat-square&logo=googlecloud)](https://g.dev/purvanshbhatt)
[![CompTIA CySA+ / Security+](https://img.shields.io/badge/CompTIA-CySA%2B%20%7C%20Security%2B%20%7C%20CSAP-red?style=flat-square&logo=comptia)](https://www.credly.com/users/purvansh-bhatt)
[![GitHub Stars](https://img.shields.io/github/stars/purvanshbhatt?style=flat-square&color=yellow)](https://github.com/purvanshbhatt)

---

## ⚡ Engineering Philosophy & Track Record

I am a Detection & Response Engineer who treats security as an end-to-end engineering discipline rather than a passive alert-routing queue. When an incident occurs, I don't stop at filing triage tickets—I actively contain the adversary, extract volatile forensic artifacts, and collaborate directly with software engineering teams to ship production IAM policies and codebase fixes.

- **50+ Real-World Incidents Contained**: Handled end-to-end cloud, identity, and SaaS incidents across AWS, GCP, and Kubernetes environments.
- **30% Faster Detection-to-Containment (MTTD/MTTR)**: Slashed incident response life-cycles through event-driven automation and ephemeral snapshotting.
- **40% Manual Triage Reduction**: Built agentic detection engineering pipelines (**ResilAI**) that eliminate SOC alert fatigue while enforcing deterministic checks against LLM hallucinations.
- **40% Attack Surface Reduction**: Engineered continuous least-privilege IAM reachability auditors and automated pull request workflows.
- **Offensive Tradecraft**: Top 5% global ranking on TryHackMe (100+ rooms, 16 badges), Level 4 Hack The Box Operator, and 5 official tournament finishes (Cyber Apocalypse, Neurogrid).

---

## 🛠️ Flagship Systems & Proof of Work

### 1. [ResilAI — Autonomous Incident Readiness & Agentic SOC Platform](https://medium.com/@purvansh95b)
*Python • FastAPI • Google Gemini API • Vector DBs • Google Cloud Run • MITRE ATT&CK & ATLAS*
- Built an agentic security operations platform that treats detection engineering like software development to eliminate alert drown.
- **Deterministic Guardrails**: Coupled deterministic AST rule analysis with LLM reasoning loops, enforcing strict JSON output schemas and embedding distance classifiers to eliminate hallucinations and false negatives.
- **Automated Production PRs**: Generates verifiable remediation code and scoped IAM policies directly into CI/CD pipelines instead of passive triage tickets.
- **Published Architecture**: Documented in depth in [*Building ResilAI: An AI Incident Readiness Platform with Gemini and Google Cloud*](https://medium.com/@purvansh95b).

### 2. [AIRS — AI-Assisted Vulnerability Scanner & Telemetry Engine](https://github.com/purvanshbhatt/AIRS)
*Python • FastAPI • Docker • Google Cloud Run • MITRE ATT&CK • OWASP Top 10*
- Architected an automated threat triage engine that reduced Mean Time to Detect (MTTD) by **65%** across 64,000+ simulated attack logs with zero telemetry loss.
- Features deterministic rule engines, intelligent reasoning agents, and automated risk scoring mapped to enterprise ATT&CK tactics.

### 3. [cloud-forensic-snapshot — Ephemeral Cloud IR & Memory Dump Engine](https://github.com/purvanshbhatt/cloud-forensic-snapshot)
*Python • AWS Boto3 • GCP Cloud SDK • Volatility 3 • SHA-256 Chain of Custody*
- Automated ephemeral cloud disk snapshot acquisition, volatile memory extraction, and evidence hash verification in under **4 minutes** (down from 2+ hours).
- Automates minute-by-minute session invalidation: neutralizes compromised AWS STS credentials by applying inline `Deny` policies bounded by `aws:TokenIssueTime < [incident_timestamp]` and correlates rogue `AssumeRole` / `GetSecretValue` events in CloudTrail.

### 4. [Adversarial-Prompt-Guard — Real-Time LLM Guardrail Framework](https://github.com/purvanshbhatt/self-healing-ai-security)
*Python • PyTorch • Vector Embeddings • OWASP LLM-01 • MITRE ATLAS*
- Engineered a real-time defense framework against prompt injection, jailbreaks, and indirect context exfiltration targeting multi-tenant LLM systems.
- Attained **98.4% detection accuracy** across the OWASP Top 10 for LLMs while maintaining a **<25ms** inference latency overhead using dual-layer semantic token filtering and latent anomaly scoring.
- [Try the Interactive Simulator on my Portfolio](https://purvanshbhatt.github.io/#simulations).

### 5. [Ransomware-Sentinel — Linux Kernel & Host Telemetry Daemon](https://github.com/purvanshbhatt/Ransomware-Sentinel)
*TypeScript • Python • eBPF • Linux /proc Forensics • cgroups*
- Endpoint behavioral monitoring agent tracking process lifecycles via `/proc/<pid>/` descriptors, memory mappings, and syscall telemetry.
- Detects container namespace escapes, `systemd`/`cron`/`LD_PRELOAD` persistence, and automated network adapter isolation upon mass file modification bursts.

---

## 🎯 Technical Proficiencies (First-Principles Rigor)

| Domain | Technical Tradecraft & Tooling |
| :--- | :--- |
| **Detection & Response Engineering** | Agentic SOC pipelines, MITRE ATT&CK & MITRE ATLAS mapping, Sigma rules, YARA signatures, Splunk (SPL), KQL / Microsoft Sentinel, Sysmon, Wazuh, Falco, Zeek. |
| **Cloud Identity & Incident Response** | AWS CloudTrail, GCP Cloud Audit Logs, STS session revocation (`aws:TokenIssueTime`), IAM reachability graph analysis, Terraform policy as code, GCP Cloud Run, AWS GuardDuty. |
| **Linux & OS Internals** | `/proc` filesystem forensics (`/proc/<pid>/exe`, `maps`, `fd`), PID/mount/network namespaces, `cgroups` isolation, syscall tracing (`execve`, `ptrace`), Volatility 3 memory analysis, persistence analysis (`systemd`, `cron`, `LD_PRELOAD`). |
| **Networking & Traffic Forensics** | TCP state machines, TLS 1.3 handshakes (SNI, cipher suites, session resumption), DNS tunneling detection (entropy analysis), Wireshark/tshark packet dissection, SSRF metadata protections (`169.254.169.254` IMDSv1 vs IMDSv2). |
| **AI Security & Red Teaming** | OWASP Top 10 for LLMs (LLM-01 Prompt Injection, Insecure Output Handling), semantic vector classifiers, adversarial fuzzing, multi-tenant AI architecture defense (Vaults, Spaces, Agent Memory). |

---

## 🏆 Verified Credentials & Operational Benchmarks

- **TryHackMe**: [purvansh95](https://tryhackme.com/p/purvansh95) — Top 5% Global Rank, Level 55, 104 completed rooms, 16 Badges (*AI Odyssey Epic 0.4%*, *Logging Legend Rare 1.6%*, *90-Day Streak*).
- **Hack The Box**: [purvansh95](https://profile.hackthebox.com/profile/019c4091-8fa1-712f-ad9f-b84b4f221dd2) — Level 4 Operator (755 XP), 5 Official CTFs (*Cyber Apocalypse 2026: The Salt Crown*, *Neurogrid: Human-Only*, *Cyber Apocalypse 2025*).
- **Google Developer Profile**: [purvanshbhatt](https://g.dev/purvanshbhatt) — Google Cloud Innovator, Google Cloud & NVIDIA Community Member, GDG Member.
- **Certifications**: CompTIA CySA+ (Cybersecurity Analyst), CompTIA Security+, CompTIA CSAP (Security Analytics Professional).
- **CTFtime**: [purvansh95b](https://ctftime.org/user/purvansh95b) • **F6S**: [purvansh-bhatt](https://www.f6s.com/purvansh-bhatt)

---

## 💼 Interactive Recruiter Fast-Track Dossier

Visiting my portfolio? Click the **`RECRUITER DOSSIER`** button or run `./recruiter_dossier.sh` in the terminal for a 1-click candidate briefing tailored to:
- **SOC & Threat Operations** (65% MTTD reduction, 0.0% telemetry loss)
- **DFIR & Incident Response** (Ransomware containment, cloud memory dumps)
- **Cloud Security Engineer** (Least-privilege IAM auditing, container security)
- **AI Security & Red Teaming** (98.4% OWASP LLM detection, <25ms latency)
- **Cyber GRC & Audit Readiness** (ISO 27001, SOC 2, HIPAA, NIST CSF)

👉 **Explore the Live Cyber Operations Platform**: [https://purvanshbhatt.github.io](https://purvanshbhatt.github.io)
