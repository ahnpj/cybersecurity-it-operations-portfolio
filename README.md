# Cybersecurity & IT Operations Portfolio

This repository serves as the **central hub and navigation guide** for my hands-on cybersecurity and IT operations portfolio.  

All labs, investigations, workflows, and playbooks are organized across multiple repositories, each focused on a different aspect of real-world security operations and incident response.

The goal of this portfolio is to demonstrate not only tool usage, but also **analyst reasoning, investigation methodology, detection engineering thinking, and operational documentation practices** aligned with real SOC and IR environments.

---

### How This Portfolio Is Organized

My work is split into **three primary areas**, each with its own repository and documentation structure:

| Area | Focus | Repository |
|--------|--------|------------|
| Incident Response & Investigations | End-to-end case investigations with evidence, analysis, reporting, and recommendations |  **incident-response-and-investigations** |
| Security Operations Workflows | Task-based SOC workflows and repeatable analyst procedures |  **security-operations-workflows** |
| SOC Playbooks & Procedures | Operational response playbooks and escalation procedures (work in progress) |  **soc-playbooks-and-procedures** |

Each repository is intentionally structured differently because they model **different real-world security functions**:
- investigations focus on **case narratives and response outcomes**
- workflows focus on **repeatable analyst tasks and tooling**
- playbooks focus on **operational response guidance**

---

###  (1) Incident Response & Investigations

**Repository:** `incident-response-and-investigations`

This repo contains full **case-style investigations** designed to simulate how incidents are handled in real SOC and IR teams.

Each investigation is structured as a **self-contained case file**, including:
- step-by-step investigation walkthroughs
- incident summaries and executive-style reports
- detection artifacts and engineering notes
- hardening and prevention recommendations
- MITRE ATT&CK technique mapping

#### Investigation Categories

Investigations are grouped by attack type and intrusion phase:

| Category | What It Covers |
|--------|------------------|
| Endpoint Compromise & Persistence | Malware execution, registry and startup persistence, scheduled tasks, host-based artifacts |
| Identity & Email Compromise | Phishing, mailbox abuse, account takeover, suspicious authentication activity |
| Intrusion & Lateral Movement | Network-based compromise, credential access, internal pivoting techniques |
| Web Application Compromise | Web shell deployment, vulnerable services, attacker interaction with servers |

Each category folder contains multiple investigations, and **each investigation uses the same standardized case structure** to reflect real incident documentation workflows.

#### Standard Investigation Case Files

Every investigation includes the following documents:

- `README.md` — scenario overview, data sources, tools, and objectives  
- `investigation-walkthrough.md` — detailed technical analysis and evidence validation  
- `incident-summary.md` — concise incident overview and key findings  
- `incident-response-report.md` — formal IR-style response documentation  
- `case-report.md` — combined narrative of attack timeline and impact  
- `detection-artifact-report.md` — detection logic, queries, and indicators  
- `detection-and-hardening-recommendations.md` — prevention and control improvements  
- `MITRE-ATT&CK-mapping.md` — technique mapping and adversary behavior alignment  

This structure mirrors how SOC analysts, detection engineers, and IR teams collaborate across **technical analysis, reporting, and security improvement planning**.

👉 **Start here:**  
`incident-response-and-investigations/`

---

### (2) Security Operations Workflows

**Repository:** `security-operations-workflows`

This repo focuses on **task-first SOC workflows** — the repeatable procedures analysts perform during monitoring, triage, and investigations.

Instead of full incidents, these labs model:
- how analysts interact with tools
- what questions they ask during triage
- how alerts and logs are validated
- how findings are documented for handoff or escalation

These workflows are intentionally written so they could later be translated into:
- SIEM detections
- automation pipelines
- SOAR playbooks

#### Workflow Categories

Workflows are grouped by operational function:

| Category | What It Covers |
|--------|------------------|
|  Detection Automation & Log Processing | Custom parsing, enrichment, behavioral signal development |
|  Endpoint Triage | Host artifact review, process analysis, persistence checks |
|  Identity & Access | Authentication review, account misuse detection, IAM validation |
|  Network Traffic Analysis | Packet inspection, suspicious flow detection, protocol analysis |
|  SIEM Detection & Log Analysis | Alert triage, query development, investigation pivots |
|  Vulnerability Management | Exposure assessment, remediation validation, risk prioritization |

### Standard Workflow Files

Each workflow includes:

- `README.md` — workflow scope, scenario, tools, and learning objectives  
- `workflow-execution.md` — step-by-step analyst actions and validation logic  
- `analyst-notes.md` — reasoning, hypotheses, and investigation thinking  
- `tool-usage-notes.md` — detailed documentation of how each tool was used and configured  

Some workflows (such as custom Python log analysis) also include:

- `automation-design-notes.md` — discussion of how manual analysis could translate into scalable detections or pipelines

These workflows are designed to show **how analysts think, not just what buttons they click**.

👉 **Start here:**  
`security-operations-workflows/`

---

### (3) SOC Playbooks & Procedures (In Progress)

**Repository:** `soc-playbooks-and-procedures`

This repository contains **operational playbooks** focused on how security teams respond once suspicious or malicious activity is confirmed.

These documents model:
- escalation paths
- containment steps
- communication procedures
- evidence handling practices

This repo is still under active development and will continue expanding as additional scenarios and response flows are added.

👉 **View playbooks:**  
`soc-playbooks-and-procedures/`

---

### Recommended Entry Points

If you are reviewing this portfolio for the first time, these are good places to start:

#### Investigation Examples
- Endpoint persistence investigation (registry / startup abuse)
- Identity compromise investigation with authentication log correlation
- Web server compromise with attacker command execution

#### Workflow Examples
- Python-based log parsing and behavioral detection workflow
- SIEM alert triage with multi-source pivoting
- Endpoint triage workflow for suspicious persistence mechanisms

(Each of the above can be found directly within the repositories linked above.)

---

### What This Portfolio Demonstrates

Across all repositories, this work is designed to demonstrate:

- Incident investigation methodology
- Evidence-based validation of alerts and suspicious behavior
- Detection logic development and tuning
- Documentation practices used in real SOC and IR teams
- Mapping of technical findings to security frameworks
- Transition from manual analysis toward detection engineering and automation

Rather than focusing on isolated tools, the emphasis is on **process, reasoning, and operational realism**.

---

### Ongoing Development

This portfolio is actively evolving. Planned future additions include:

- Additional end-to-end incident investigations
- Expanded automation design documentation
- More SOC operational playbooks
- Detection engineering–focused workflows

Updates are added continuously as new labs and scenarios are completed.
