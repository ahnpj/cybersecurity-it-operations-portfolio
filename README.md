# Cybersecurity & IT Operations Portfolio

This repository serves as the **central hub and navigation guide** for my hands-on cybersecurity and IT operations portfolio.

All investigations, operational workflows, and response playbooks are organized across multiple repositories, each focused on a different aspect of real-world security operations and incident response.

The goal of this portfolio is to demonstrate not only tool usage, but also **analyst reasoning, investigation methodology, detection engineering thinking, and operational documentation practices** aligned with real SOC and IR environments.

---

### How This Portfolio Is Organized

My work is split into **three primary areas**, each with its own repository and documentation structure:

| Area | Focus | Repository |
|--------|--------|------------|
| Incident Response & Investigations | End-to-end case investigations with evidence analysis, reporting, and security recommendations | **incident-response-and-investigations** |
| Security Operations Workflows | Task-based SOC workflows and repeatable analyst procedures | **security-operations-workflows** |
| SOC Playbooks & Procedures | Operational response playbooks and escalation procedures (in progress) | **soc-playbooks-and-procedures** |

Each repository is intentionally structured differently because they model **distinct real-world security functions**:
- investigations focus on **case narratives and response outcomes**
- workflows focus on **repeatable analyst tasks and tooling**
- playbooks focus on **operational response guidance**

---

### (1) Incident Response & Investigations

**Repository:** `incident-response-and-investigations`

This repository contains full **case-style investigations** designed to simulate how incidents are handled in real SOC and incident response teams. Each investigation is structured as a **self-contained case file**, including:

- detailed investigation walkthroughs and evidence validation
- incident summaries and executive-style overviews
- formal incident response reports
- complete case narratives and attack timelines
- detection artifact analysis and engineering notes
- detection and hardening recommendations
- MITRE ATT&CK technique mapping

#### Investigation Categories (Investigations are grouped by attack type and intrusion phase)

| Category | What It Covers |
|--------|------------------|
| Endpoint Compromise & Persistence | Malware execution, registry and startup persistence, scheduled tasks, host-based artifacts |
| Identity & Email Compromise | Phishing, mailbox abuse, account takeover, suspicious authentication activity |
| Intrusion & Lateral Movement | Network-based compromise, credential access, and internal pivoting techniques |
| Web Application Compromise | Web shell deployment, vulnerable services, and attacker interaction with servers |

Each category folder contains multiple investigations, and **each investigation uses the same standardized case structure** to reflect real incident documentation workflows.

👉 **Start here:**  
`incident-response-and-investigations/`

---

### (2) Security Operations Workflows

**Repository:** `security-operations-workflows`

This repository focuses on **task-first SOC workflows** — the repeatable procedures analysts perform during monitoring, triage, and investigation activities. These workflows are written so they can later be translated into SIEM detections, automation pipelines, and SOAR playbooks.

Instead of full incidents, these workflows model:
- how analysts interact with security and monitoring tools
- how alerts and telemetry are validated
- how investigation pivots are performed
- how findings are documented for escalation or handoff

#### Workflow Categories (Workflows are grouped by operational function)

| Category | What It Covers |
|--------|------------------|
| Detection Automation & Log Processing | Custom parsing, enrichment, and behavioral signal development |
| Endpoint Triage | Host artifact review, process analysis, and persistence checks |
| Identity & Access | Authentication review, account misuse detection, and IAM validation |
| Network Traffic Analysis | Packet inspection, suspicious flow detection, and protocol analysis |
| SIEM Detection & Log Analysis | Alert triage, query development, and investigation pivots |
| Vulnerability Management | Exposure assessment, remediation validation, and risk prioritization |

#### Standard Workflow Files

Each workflow includes:

- `README.md` — workflow scope, scenario context, tools, and objectives  
- `workflow-execution.md` — step-by-step analyst actions and validation logic  
- `analyst-notes.md` — reasoning, hypotheses, and investigative thought process  
- `tool-usage-notes.md` — detailed documentation of how each tool was used and configured  

These workflows are designed to show **how analysts think, not just what actions they perform**. Some workflows (such as custom Python log analysis) also include:

- `automation-design-notes.md` — discussion of how manual analysis could translate into scalable detections or enrichment pipelines

👉 **Start here:**  
`security-operations-workflows/`

---

### (3) SOC Playbooks & Procedures (In Progress)

**Repository:** `soc-playbooks-and-procedures`

This repository contains **operational playbooks** focused on how security teams respond once suspicious or malicious activity is confirmed. This repository is under active development and will continue expanding as additional response scenarios and procedures are added.

These documents model:
- escalation paths and decision points
- containment and remediation steps
- communication procedures
- evidence handling and documentation practices

**View playbooks:**  
`soc-playbooks-and-procedures/`

---

### Recommended Entry Points

If you are reviewing this portfolio for the first time, the following are good places to start:

#### Investigation Examples
- Endpoint persistence investigation (registry and startup abuse)
- Identity compromise investigation with authentication log correlation
- Web server compromise with attacker command execution

#### Workflow Examples
- Python-based log parsing and behavioral detection workflow
- SIEM alert triage with multi-source investigation pivots
- Endpoint triage workflow for suspicious persistence mechanisms

(Each of the above can be found directly within the repositories linked above.)

---

### What This Portfolio Demonstrates

Rather than focusing on isolated tools, the emphasis is on **process, reasoning, and operational realism**. Across all repositories, this work is designed to demonstrate:

- Incident investigation methodology and evidence validation
- Detection logic development and tuning
- Operational documentation and reporting practices
- Mapping of technical findings to security frameworks
- Transition from manual investigation toward detection engineering and automation

---

### Ongoing Development

This portfolio continues to evolve as new investigations, workflows, and playbooks are added, including:

- additional end-to-end incident investigations
- expanded automation and detection engineering design notes
- additional SOC operational playbooks
- further workflow coverage across security operations domains
