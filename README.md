# Purvansh Bhatt
### **Incident Response & Detection Engineer | Cloud & AI Security | Creator of ResilAI & AI-Red-Team-Lab**
New York, NY • [Interactive Portfolio](https://purvanshbhatt.github.io) • [LinkedIn](https://linkedin.com/in/purvanshbhatt) • [Medium Field Notes](https://medium.com/@purvansh95b) • [Email](mailto:purvansh95b@gmail.com)

> *"Security is a core software engineering problem, not a compliance checklist. Decisiveness. Simplicity. Job's Not Finished."*

[![TryHackMe Top 5%](https://img.shields.io/badge/TryHackMe-Top%205%25%20Global-teal?style=flat-square&logo=tryhackme)](https://tryhackme.com/p/purvansh95)
[![Hack The Box Level 4](https://img.shields.io/badge/HackTheBox-Level%204%20Operator-green?style=flat-square&logo=hackthebox)](https://profile.hackthebox.com/profile/019c4091-8fa1-712f-ad9f-b84b4f221dd2)
[![Google Cloud Innovator](https://img.shields.io/badge/Google%20Cloud-Innovator%202026-blue?style=flat-square&logo=googlecloud)](https://g.dev/purvanshbhatt)
[![CompTIA CySA+ / Security+](https://img.shields.io/badge/CompTIA-CySA%2B%20%7C%20Security%2B%20%7C%20CSAP-red?style=flat-square&logo=comptia)](https://www.credly.com/users/purvansh-bhatt)
[![GitHub Stars](https://img.shields.io/github/stars/purvanshbhatt?style=flat-square&color=yellow)](https://github.com/purvanshbhatt)

---

## ⚡ Engineering Philosophy & Incident Response Track Record

I am an Incident Response & Detection Engineer who builds detection and containment systems with an attacker mindset. When an active breach or anomalous session occurs, I don't just route triage tickets—I actively contain the adversary session, trace telemetry across cloud audit streams and host kernels, and collaborate directly with software engineering teams to ship production IAM policies and codebase fixes.

- **50+ End-to-End Cloud & Identity Incidents Contained**: Handled complex incidents across AWS IAM, GCP Cloud Run, Kubernetes pods, and SaaS identity providers.
- **30% Reduction in Detection-to-Containment (MTTD/MTTR)**: Slashed response life-cycles through event-driven automation and ephemeral snapshotting.
- **40% Manual Triage Reduction**: Built agentic detection engineering pipelines (**ResilAI**) that eliminate SOC alert fatigue while enforcing deterministic checks against LLM hallucinations.
- **40% Attack Surface Reduction**: Engineered continuous least-privilege IAM reachability auditors and automated pull request workflows.
- **Offensive Tradecraft**: Top 5% global ranking on TryHackMe (100+ rooms, 16 badges), Level 4 Hack The Box Operator, and 5 official tournament finishes (Cyber Apocalypse, Neurogrid).

---

## 🛠️ Production Systems & Proof of Work

| System | Role & Architecture | Stack & Key Deliverables |
| :--- | :--- | :--- |
| **[ResilAI (AIRS)](https://medium.com/@purvansh95b)** | **Deterministic Pre-LLM Logic Firewall & AI Incident Readiness/Reconstruction Platform** | **Python, FastAPI, GCP Cloud Run, MITRE ATLAS**<br>• Dual-layer inspection engine combining deterministic AST syntax checks with semantic boundary classifiers.<br>• Inspects RAG context payloads (`MITRE AML.T0031`) to block prompt injection & data exfiltration before LLM inference.<br>• Emits structured SIEM JSON audit telemetry and triggers automated post-incident reconstruction playbooks.<br>• *Architecture documented in depth on [Medium](https://medium.com/@purvansh95b).* |
| **[AI-Red-Team-Lab](https://github.com/purvanshbhatt/self-healing-ai-security)** | **Adversarial LLM Evaluation Pipeline Feeding Detection Rules** | **Python, Garak, Microsoft PyRIT, Promptfoo, OWASP LLM-01**<br>• Automated adversarial harness benchmarking multi-tenant AI systems against jailbreaks, system prompt extractions, and tool-calling abuse.<br>• Automatically converts discovered adversarial bypasses into deterministic Sigma detection rules and pre-LLM regex/vector guardrails.<br>• Evaluates cross-tenant RAG vector isolation and agentic tool boundaries under continuous fuzzing. |
| **[OriginTrace / patchproof](https://github.com/purvanshbhatt/patchproof)** | **Automated Supply-Chain AST Delta Detection & Remediation Verification** | **Python, AST Parsing, Git Hooks, GitHub Actions**<br>• Automated framework performing AST differential analysis across third-party dependencies and internal security patches.<br>• Prevents supply-chain malicious code injection by verifying that security patches remediate CVEs without introducing runtime regressions.<br>• Validated across 50+ dependency updates with automated cryptographic integrity attestations. |
| **[cloud-forensic-snapshot](https://github.com/purvanshbhatt/cloud-forensic-snapshot)** | **Ephemeral Cloud IR & Volatile Memory Acquisition Engine** | **Python, AWS Boto3, GCP SDK, Volatility 3, SHA-256 Chain of Custody**<br>• Automated cloud disk capture and volatile memory extraction under 4 minutes with cryptographically signed hashes.<br>• Minute-by-minute session invalidation: revokes active AWS STS tokens via inline `Deny` policies (`aws:TokenIssueTime < [incident_timestamp]`) and traces rogue `AssumeRole` / `GetSecretValue` events in CloudTrail. |
| **[Ransomware-Sentinel](https://github.com/purvanshbhatt/Ransomware-Sentinel)** | **Linux Kernel & Host Telemetry Daemon** | **TypeScript, Python, eBPF, Linux /proc Forensics, cgroups**<br>• Real-time host behavioral agent inspecting `/proc/<pid>/` descriptors, memory mappings (`maps`), and syscalls (`execve`, `ptrace`).<br>• Detects container namespace escapes, `systemd`/`cron`/`LD_PRELOAD` persistence mechanisms, and triggers instant network adapter containment. |

---

## 🎯 Technical Proficiencies (First-Principles Rigor)

| Domain | Technical Tradecraft & Tooling |
| :--- | :--- |
| **Detection & Response Engineering** | Agentic SOC pipelines, MITRE ATT&CK & MITRE ATLAS mapping, Sigma rules, YARA signatures, Splunk (SPL), KQL / Microsoft Sentinel, Sysmon, Wazuh, Falco, Zeek. |
| **Cloud Identity & Incident Response** | AWS CloudTrail, GCP Cloud Audit Logs, STS session revocation (`aws:TokenIssueTime`), IAM reachability graph analysis, Terraform policy as code, GCP Cloud Run, AWS GuardDuty, Okta/SAML session containment. |
| **Linux & OS Internals** | `/proc` filesystem forensics (`/proc/<pid>/exe`, `maps`, `fd`), PID/mount/network namespaces (`unshare`, `nsenter`), `cgroups` isolation, syscall tracing (`execve`, `ptrace`), Volatility 3 memory analysis, persistence analysis (`systemd`, `cron`, `LD_PRELOAD`). |
| **Networking & Traffic Forensics** | TCP state machines, TLS 1.3 handshakes (SNI, cipher suites, session resumption), DNS tunneling detection (entropy analysis), Wireshark/tshark packet dissection, SSRF metadata protections (`169.254.169.254` IMDSv1 vs IMDSv2). |
| **AI Security & Red Teaming** | OWASP Top 10 for LLMs (LLM-01 Prompt Injection, Insecure Output Handling), pre-LLM deterministic firewalls, semantic vector classifiers, adversarial fuzzing (Garak, PyRIT, Promptfoo), multi-tenant AI architecture defense (Vaults, Spaces, Agent Memory). |

---

## 🏆 Verified Credentials & Operational Benchmarks

- **TryHackMe**: [purvansh95](https://tryhackme.com/p/purvansh95) — Top 5% Global Rank, Level 55, 104 completed rooms, 16 Badges (*AI Odyssey Epic 0.4%*, *Logging Legend Rare 1.6%*, *90-Day Streak*).
- **Hack The Box**: [purvansh95](https://profile.hackthebox.com/profile/019c4091-8fa1-712f-ad9f-b84b4f221dd2) — Level 4 Operator (755 XP), 5 Official CTFs (*Cyber Apocalypse 2026: The Salt Crown*, *Neurogrid: Human-Only*, *Cyber Apocalypse 2025*).
- **Google Developer Profile**: [purvanshbhatt](https://g.dev/purvanshbhatt) — Google Cloud Innovator, Google Cloud & NVIDIA Community Member, GDG Member.
- **Certifications**: CompTIA CySA+ (Cybersecurity Analyst), CompTIA Security+, CompTIA CSAP (Security Analytics Professional).
- **CTFtime**: [purvansh95b](https://ctftime.org/user/purvansh95b) • **F6S**: [purvansh-bhatt](https://www.f6s.com/purvansh-bhatt)

---

## 💼 Interactive Recruiter Fast-Track Dossier & Live Platform

Visiting my portfolio? Click the **`RECRUITER DOSSIER`** button or run `./recruiter_dossier.sh` in the terminal for a 1-click candidate briefing tailored to:
- **SOC & Threat Operations** (65% MTTD reduction, 0.0% telemetry loss)
- **DFIR & Incident Response** (Ransomware containment, cloud memory dumps)
- **Cloud Security Engineer** (Least-privilege IAM auditing, container security)
- **AI Security & Red Teaming** (98.4% OWASP LLM detection, <25ms latency)
- **Cyber GRC & Audit Readiness** (ISO 27001, SOC 2, HIPAA, NIST CSF)

👉 **Explore the Live Cyber Operations Platform**: [https://purvanshbhatt.github.io](https://purvanshbhatt.github.io)
