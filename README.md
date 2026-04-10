# **Threat Hunting & Incident Analysis Lab (Cyber Range)**

## **Overview**

This repository presents a collection of structured **threat hunting investigations** conducted within controlled cyber range environments. Each write-up demonstrates a methodical, evidence-driven approach to identifying and analyzing adversary behavior using endpoint telemetry and log analytics.

The focus is not only on outcomes, but on the **analytical process** how an analyst forms hypotheses, validates assumptions, and incrementally builds a complete picture of an incident.

---

## Objectives

This portfolio is designed to:

- Demonstrate practical **threat hunting capabilities in simulated enterprise environments**
- Showcase hypothesis-driven investigation techniques aligned with real-world SOC workflows
- Apply structured analysis using endpoint telemetry and log data
- Map observed behavior to the **MITRE ATT&CK** framework
- Present clear, reproducible, and portfolio-ready investigations

---
## Methodology

Each investigation follows a flag-based progression model, reflecting how real-world analysts work through incidents in stages rather than arriving at conclusions instantly.

The methodology emphasizes:

- Incremental discovery
- Context-driven analysis
- Correlation of multiple weak signals into meaningful findings
- Continuous refinement of investigative hypotheses


---
##  Threat Hunt Structure

Each threat hunt follows a consistent **flag-by-flag structure**, mirroring how analysts work incidents in stages rather than all at once.

---

## Investigation Structure

Each threat hunt is organized into the following sections:

### 1. Scenario Overview

Business and technical context
Initial analyst position
Known vs unknown variables at the start of the investigation

### 2. Hunting Hypothesis
Initial suspicion or anomaly
Expected attacker objectives
Anticipated tactics and techniques

### 3. Data Sources
Endpoint telemetry (process, file, registry, network activity)
EDR advanced hunting data
Log analytics and supporting signals

---

##  Flag-Based Analysis

Each investigation is broken into sequential flags, representing key analytical milestones.

For every flag, the following is documented:

- **Objective** – What the analyst is attempting to uncover
- **Context** – Why the activity is relevant to the investigation
- **Hunting Focus** – Behavioral patterns or anomalies being explored
- **Query Logic** – KQL or equivalent logic used to surface evidence
- **Findings** – Artifacts identified during analysis
- **MITRE ATT&CK Mapping** – Associated tactics and techniques
- **Outcome** – Confirmed result of the investigation step



## Typical Investigation Flow

Investigations may include stages such as:

- Initial execution or access
- Discovery and reconnaissance
- Persistence mechanisms
- Defense evasion techniques
- Data collection and staging
- Lateral movement
- Command-and-control (C2) activity
- Final impact or objective

Each stage builds upon previous findings to maintain **analytical continuity**.

---

## Example Flag Progression

- Flag 1 – Initial suspicious execution  
- Flag 2 – Abnormal command-line behavior  
- Flag 3 – Malware staging directory  
- Flag 4 – Persistence via scheduled task or autorun  
- Flag 5 – Defense evasion indicators  
- Flag 6 – Data collection and staging  
- Flag 7 – Beaconing / C2 behavior  
- Flag 8 – Impact or final objective  

The exact number and theme of flags vary by scenario.

---

## Analyst Assessment

After the final flag, each hunt concludes with:

- Timeline summary
- Adversary intent assessment
- Kill chain reconstruction
- Confidence level of conclusions

---

## MITRE ATT&CK Summary

- Techniques observed across all flags
- Tactic frequency and clustering
- Heatmap-style overview (where applicable)

---

##  Detection & Mitigation Recommendations

- Suggested detections based on observed behavior
- Logging or telemetry improvements
- Defensive control hardening
- Lessons learned for future hunts

---

## 🛠 Tools & Techniques

Hunts commonly leverage:

- Endpoint Detection & Response telemetry
- Advanced hunting queries (KQL-style logic)
- Log analytics platforms
- MITRE ATT&CK framework
- Windows internals and process analysis

The focus is on **reasoning and methodology**, not vendor-specific dashboards.

---

## Intended Audience

- SOC analysts and threat hunters
- Blue-team practitioners
- Cybersecurity students and career-transitioners
- Hiring managers reviewing applied security skills

Basic familiarity with security telemetry is assumed.

---

## Disclaimer

All activity in this repository is part of **controlled cyber range simulations**.  
No real-world malware, victims, or production environments are involved.

---

## Why Flag-Based Hunting Matters

Threat hunting is rarely solved in one query.  
Breaking investigations into flags mirrors how analysts actually work: forming hypotheses, validating assumptions, and refining scope as new evidence emerges.

These write-ups are designed to reflect that reality.

---

## Portfolio Context

This repository is part of a broader cybersecurity portfolio demonstrating:
- Threat hunting
- Detection engineering
- Incident analysis
- Defensive research

Feedback and discussion are welcome.
