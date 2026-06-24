# CySA+ Analyst Training Simulations

A browser-based CySA+ (CS0-003) analyst training simulation platform built to help students strengthen cybersecurity reasoning, threat analysis workflow, and performance-style exam readiness.

This project contains original, instructor-created simulations designed for students preparing for the CompTIA CySA+ certification and entry-level SOC analyst roles. The simulations focus on high-return CS0-003 concepts that require applied decision-making — the kind of thinking that separates analysts who can identify threats from analysts who can respond to them.

The goal is not just to help students memorize terms.

The goal is to help students think like analysts.

---

## Live Simulation Platform

[Launch CySA+ Analyst Training Simulations](https://shanemckenney.github.io/CySA-Simulations/)

Interactive CySA+ analyst training simulations focused on:

- IOC triage and threat investigation
- SIEM log analysis and correlation
- Vulnerability assessment and prioritization
- Endpoint behavioral analysis
- Incident ticket classification
- Kill chain and adversary behavior mapping
- Email header analysis for phishing detection

---

## Project Purpose

As a cybersecurity instructor, I built these simulations to give students practical, repeatable exposure to CySA+ concepts before they encounter scenario-driven questions, hands-on labs, or certification-style performance tasks.

Many students can define a concept but struggle when they must apply that concept in context.

These simulations help bridge that gap by requiring students to:

- Read realistic security scenarios and analyst workflows carefully
- Identify indicators of compromise and key context clues
- Eliminate noise and distractors from real signals
- Select appropriate analyst actions and escalation decisions
- Understand why a decision is correct or incorrect
- Practice applied SOC analyst decision-making under time pressure

---

## Current Simulation Library

### 1. IOC Triage — Analyst Decision Lab

Students review a set of evidence artifacts, make triage decisions on each indicator, advance to a telemetry and assessment phase, then provide a final classification with justification.

**Skills reinforced:**

- Indicator of compromise recognition
- Evidence triage prioritization
- Benign vs. malicious discrimination
- Analyst reasoning and justification
- False positive reduction
- Telemetry-based decision refinement

---

### 2. SIEM Log Sifter

Students analyze raw SIEM log data, identify anomalous entries, and determine which events warrant escalation versus which represent normal baseline activity.

**Skills reinforced:**

- SIEM alert interpretation
- Log-based threat detection
- Baseline vs. anomaly identification
- Event correlation fundamentals
- Escalation decision-making

---

### 3. SOC Log Correlation

Students correlate log data across multiple sources — host, network, and authentication — to reconstruct an event timeline and identify the scope of a potential incident.

**Skills reinforced:**

- Multi-source log correlation
- Event timeline reconstruction
- Lateral movement detection
- Authentication anomaly analysis
- Scope and impact assessment

---

### 4. Endpoint Behavioral Analysis

Students review endpoint telemetry and process activity to identify signs of compromise, including suspicious parent-child process relationships, unusual execution paths, and persistence indicators.

**Skills reinforced:**

- Endpoint detection and response concepts
- Process behavior analysis
- Persistence mechanism recognition
- Host-based indicator identification
- Sysmon and endpoint log interpretation

---

### 5. Email Header Analyzer

Students analyze email header data to identify spoofing, phishing infrastructure, authentication failures, and social engineering indicators.

**Skills reinforced:**

- Email header structure and fields
- SPF, DKIM, and DMARC interpretation
- Phishing infrastructure recognition
- Sender impersonation detection
- Social engineering pattern analysis

---

### 6. Incident Ticket Analysis

Students classify and prioritize incoming incident tickets based on severity, affected assets, and available evidence, then select appropriate initial response actions.

**Skills reinforced:**

- Incident classification and severity assessment
- Priority triage in a SOC queue
- Asset criticality consideration
- Initial response selection
- Incident documentation concepts

---

### 7. Kill Chain Mapping

Students map observed adversary behaviors to Cyber Kill Chain phases and identify which defensive actions apply at each stage of an attack progression.

**Skills reinforced:**

- Cyber Kill Chain framework
- Adversary behavior mapping
- Phase-appropriate defensive response
- Attack lifecycle awareness
- Threat intelligence application

---

### 8. OWASP CVSS Triage

Students apply CVSS scoring components — base, temporal, and environmental metrics — to prioritize vulnerability remediation across a simulated asset inventory.

**Skills reinforced:**

- CVSS base, temporal, and environmental scoring
- Risk-based vulnerability prioritization
- Asset criticality weighting
- Environmental modifier application
- Remediation sequencing

---

### 9. Resource Anomaly Correlation

Students correlate resource usage anomalies — CPU spikes, memory consumption, unusual network throughput — against process and authentication data to identify potential threat activity.

**Skills reinforced:**

- Performance anomaly analysis
- Resource-based threat detection
- Correlation across data sources
- Cryptojacking and data exfiltration pattern recognition
- Baseline deviation assessment

---

### 10. Software Vulnerability Sandbox

Students review simulated vulnerability scan output and application behavior data to identify vulnerable components, assess exploitability, and recommend remediation.

**Skills reinforced:**

- Vulnerability scan output interpretation
- Exploitability assessment
- Patch and remediation prioritization
- Dependency and component risk analysis
- Vulnerability management workflow

---

### 11. Vulnerability Prioritization and Remediation

Students work through a prioritized remediation workflow, balancing CVSS scores, asset criticality, threat intelligence context, and resource constraints to build a defensible remediation plan.

**Skills reinforced:**

- Risk-based remediation planning
- CVSS contextualization
- Threat intelligence integration
- Stakeholder communication concepts
- Remediation sequencing and justification

---

## Instructional Design Approach

These simulations are built around an applied learning model:

Scenario exposure → Student action → Immediate feedback → Explanation → Retry

Each activity is designed to give students a practical decision-making experience rather than a passive review experience.

The simulations can be used for:

- Instructor-led review sessions
- Individual student practice
- Small-group lab activities
- Exam readiness preparation
- Topic reinforcement after lecture
- Scenario-based class discussion
- Cybersecurity fundamentals practice for entry-level roles

---

## Content Disclaimer

This project contains original, instructor-created training content.

It does not contain:

- Actual CompTIA exam questions
- Exam dumps or brain dump material
- Proprietary certification content
- Confidential testing material
- Questions reproduced from certification exams

All scenarios, artifacts, IP addresses, hostnames, file names, and evidence data used in these simulations are entirely fictional and were created specifically for instructional purposes. Any resemblance to real systems, networks, or incidents is coincidental.

The simulations are designed to reinforce general cybersecurity analyst concepts and applied reasoning skills through original scenario-based exercises.

CySA+ (CS0-003) is a trademark of CompTIA. This project is independent and is not affiliated with, endorsed by, or sponsored by CompTIA.

---

## AI-Assisted Development

This project was developed using a combination of instructor expertise and AI-assisted coding workflows.

Tools used:

- Claude (Anthropic)
- Gemini
- VS Code
- GitHub
- GitHub Pages

The development process combined cybersecurity instruction knowledge, simulation design, and iterative AI-assisted coding. The instructional logic, scenario content, analyst decision-making objectives, and cybersecurity reasoning frameworks were intentionally guided and reviewed by a human instructor throughout development.

AI was used as a development accelerator for UI refinement, refactoring, styling, and documentation. The cybersecurity content itself — the scenarios, the indicators, the triage logic, the feedback reasoning — reflects instructor domain expertise and was not generated by AI.

---

## Technology Stack

This project intentionally uses a simple, transparent, and portable technology stack:

- HTML
- CSS
- JavaScript
- GitHub Pages

No frameworks, backend services, databases, analytics, tracking scripts, or external libraries are required.

This keeps the platform:

- Easy to inspect
- Easy to host
- Easy to modify
- Easy to test
- Easy to use in class
- Low-risk from a privacy and security standpoint

---

## Security and Privacy Design

Because this project is cybersecurity-focused, it is built with secure development principles in mind.

Current safeguards include:

- Static-site architecture
- No user accounts
- No authentication system
- No backend database
- No student data collection
- No analytics or tracking
- No hidden form submission
- No external dependencies
- No third-party scripts
- No score storage
- No personally identifiable information collection

---

## Privacy Statement

These simulations run entirely in the browser and do not collect, transmit, or store student information.

The project does not collect:

- Names
- Email addresses
- Student IDs
- Scores
- Completion data
- Interaction logs
- Device information
- Analytics data

Any scoring or feedback occurs locally in the browser during the activity and is not retained after the session ends.

---

## How to Use

### Use Through GitHub Pages

Open the published GitHub Pages site and launch simulations from the dashboard.

### Run Locally

Clone the repository:

```bash
git clone https://github.com/shanemckenney/CySA-Simulations.git
```

Open the project folder and launch `index.html` from the root, or use the VS Code Live Server extension for best results.

---

## Recommended Instructor Use

These simulations work best as active learning activities.

Suggested classroom flow:

1. Introduce the analyst concept or domain area briefly.
2. Have students attempt the simulation individually or in pairs.
3. Ask students to explain their triage and classification reasoning.
4. Review the feedback together as a class.
5. Connect the scenario back to CySA+ exam objectives and real SOC workflows.
6. Allow students to retry after discussion.

The strongest learning occurs when students explain *why* a decision is correct, not just whether they selected the right option.

---

## Recommended Student Use

Students should approach each simulation as a cybersecurity analyst reasoning exercise.

Recommended process:

1. Read the scenario and artifact data carefully.
2. Identify the technical indicators and context clues.
3. Watch for noise and distractors — not everything is malicious.
4. Make your triage or classification decision based on available evidence.
5. Review the explanation and feedback.
6. Retry until the analyst reasoning makes sense, not just the answer.

The goal is not just to get the answer right.

The goal is to understand why the answer is right.

---

## Repository Structure

```
CySA-Simulations/
│
├── simulations/
│   ├── email-header-analyzer/
│   │   └── index.html
│   ├── endpoint-behavioral-analysis/
│   │   └── index.html
│   ├── incident-ticket-analysis/
│   │   └── index.html
│   ├── ioc-triage/
│   │   └── index.html
│   ├── kill-chain/
│   │   └── index.html
│   ├── owasp-cvss-triage/
│   │   └── index.html
│   ├── resource-anomaly-correlation/
│   │   └── index.html
│   ├── siem-log-sifter/
│   │   └── index.html
│   ├── soc-log-correlation/
│   │   └── index.html
│   ├── software-vulnerability-sandbox/
│   │   └── index.html
│   └── vulnerability-prioritization-remediation/
│       └── index.html
│
├── chrome.css
├── index.html
└── README.md
```

---

## Contributions

This project is maintained as an instructor-developed training resource.

Suggestions for simulation improvements, accessibility enhancements, documentation updates, additional scenarios, and UI improvements are welcome through the standard GitHub workflow.

**Please do not submit:**

- Copied exam questions
- Exam dumps or brain dump material
- Proprietary certification content
- Confidential testing material
- Questions reproduced from actual certification exams

Submissions containing the above will not be accepted and will be removed.

---

## Author

Created by a cybersecurity instructor, SOC analyst educator, and simulation developer focused on:

- CySA+ exam readiness
- Scenario-based analyst training
- Entry-level SOC analyst preparation
- Applied threat analysis workflow practice
- AI-assisted educational tooling

---

## License

See the `LICENSE` file for details.

---

## Final Note

These simulations are designed to help learners build the analyst instincts, reasoning patterns, and threat recognition habits that certification knowledge alone cannot provide.

A strong CySA+ analyst does not just know what an IOC is. They know how to triage it, contextualize it, and make a defensible call on it under time pressure.

That is what this lab is built to practice.
