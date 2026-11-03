# Hi, I'm Fares 👋

### I love figuring out how things work, and how they break.

I'm a 3rd-semester Computer Science (Informatik) student at TU Darmstadt, focused on **cybersecurity and AI security**: how products, LLMs and AI agents can be attacked, tested and made safer. This semester I'm taking part in the **Hacker Contest (usd AG × TU Darmstadt)**, a pentesting course with admission by a solo entrance challenge. I learn by building hands-on labs in my own accounts and documenting every step, including what went wrong and what I'd do better.

## 🚀 Projects

### 🇪🇺 CRA Copilot: EU Cyber Resilience Act 24-Hour Vulnerability Reporting
Since 11 September 2026, the EU Cyber Resilience Act (Art. 14) requires manufacturers to report an actively exploited vulnerability within 24 hours. This open-source tool reads a product's SBOM, checks every component against OSV.dev and the CISA KEV list (it caught Log4Shell live in a demo product) and drafts the early warning in German and English; a human approves every report and the tool never sends anything. I attacked it with an AI pentester (Strix): 11 findings, all addressed with regression tests written first. 1,450 tests pass.
→ https://github.com/feres-salhi/cra-copilot

### 🏛️ SÜSIE: AI Compliance Review Assistant (Futury Build Days hackathon)
Team project from a 32-hour hackathon by Futury, hessian.AI, ITSG and MAINGAU: an AI assistant supporting ITSG's legally required review of payroll software. I built the security and trust layer: a rule checker with an input guard (14/14 attacks stopped, 0 false alarms), verified retrieval that checks every AI quote against 1,219 rulebook sections, a privacy airlock that pseudonymizes personal data before any AI call (0 of 224 planted values leaked), and a tamper-evident receipt for reports. 167 tests pass.
→ https://github.com/feres-salhi/futury-itsg-review-assistant

### 🧱 AgentWarden: AI Agent Containment and Red-Teaming
A tool-using AI agent contained in layers inspired by NVIDIA's Open Agent Safety Platform: a hardened Docker sandbox, a deny-by-default OPA policy checked before every tool call, an audit log, and a watchdog that kills the agent in about 430 ms. 13 automated promptfoo attacks found a case-sensitivity bypass that leaked a honeytoken; I fixed the policy and verified 13/13.
→ https://github.com/feres-salhi/agentwarden

### 📡 ADS-B Spoofing Detector: ML Attack Detection on Live Aircraft Signals
Live aircraft broadcasts captured over the Rhine-Main area with a 27-euro software-defined radio, turned into flight tracks, and fed to an Isolation Forest anomaly detector. Red-teamed with synthetic spoofing attacks: 100% caught on held-out data with a 1.6% false-alarm rate, and its limits documented.
→ https://github.com/feres-salhi/adsb-security-lab

### 🛡️ Mini SOC in the Cloud: Elastic SIEM + AI Alert Triage
A Windows server on AWS monitored by Elastic's EDR agent, a custom detection rule mapped to MITRE ATT&CK (T1033), and automated triage: each alert goes to Tines, an AI writes a summary, and the analyst gets an email, with no human in between.
→ https://github.com/feres-salhi/elastic-siem-ai-soc-automation

## 🛠️ Skills & tools

**AI security:** prompt injection (direct & indirect) · agent red-teaming (promptfoo) · AI agent containment · LLM privacy guards · adversarial ML testing · OWASP Top 10 for LLM and Agentic Applications
**Security operations:** Elastic Security (SIEM/EDR) · detection rules (KQL) · MITRE ATT&CK mapping · Tines (SOAR) · AWS EC2 & security groups
**Product & security engineering:** vulnerability management (SBOM, OSV, CISA KEV) · EU Cyber Resilience Act (Art. 14) · Docker hardening · Open Policy Agent (Rego) · integrity checks (SHA-256, HMAC)
**Programming:** Python · Java · C · pytest · scikit-learn
**Tools:** Git & GitHub · GitHub Actions (CI/CD) · Anthropic API · Docker

## 🌍 About me

🎓 Computer Science (Informatik) at TU Darmstadt
🗣️ German C1 · English C1 · French C1
🔐 Hacker Contest WiSe 2026/27 (usd AG × TU Darmstadt)

---

📫 **Let's connect:** [LinkedIn](https://www.linkedin.com/in/fares-salhi-03b53530a) · [Portfolio](https://faressalhi.com)
