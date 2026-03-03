# 🔐 NovaPay Security Controls Dashboard
### CompTIA Security+ Project — Domain 1: General Security Concepts

> **Note:** NovaPay Inc. is a fictional company created for educational purposes. All data, controls, and scenarios are simulated to reflect a realistic fintech security environment.

---

## 📌 Project Overview

This project is a hands-on application of **CompTIA Security+ Domain 1 — General Security Concepts**, built as part of an active study and portfolio initiative. The goal was to go beyond memorizing definitions and instead apply security control frameworks to a realistic business scenario.

The deliverable is a fully interactive **HTML Security Controls Dashboard** mapping 34 security controls across four categories for NovaPay Inc. — a fictional 50-person fintech startup processing digital payments.

**Live Dashboard →** `https://reizaimi.github.io/web-security-dashboard/`

---

## 🏢 About NovaPay Inc. (Fictional Company)

| Field | Details |
|---|---|
| **Company** | NovaPay Inc. *(fictional)* |
| **Industry** | Fintech — Digital Payments & Money Transfers |
| **Size** | 50 employees |
| **Founded** | 2021 (fictional) |
| **HQ** | Austin, TX (fictional) |
| **Infrastructure** | AWS (us-east-1), cloud-native |
| **Compliance** | PCI-DSS Level 1, SOC 2 Type II |
| **Daily Volume** | $2.3M+ in simulated transactions |

NovaPay was designed as a realistic threat-rich environment — a small team handling sensitive financial data, operating under strict compliance requirements, with a 2-person IT team. This makes it an ideal scenario for stress-testing security control coverage.

---

## 🎯 What This Project Covers

### Security Control Categories
| Category | Controls Mapped |
|---|---|
| Technical | 11 |
| Managerial | 7 |
| Operational | 8 |
| Physical | 6 |

### Control Types Applied
- **Preventive** — stops incidents before they occur
- **Detective** — identifies threats as they happen
- **Corrective** — restores systems after an incident
- **Deterrent** — discourages attackers or policy violations
- **Compensating** — fallback when primary controls are unavailable
- **Directive** — mandates behavior through policy

### Each Control Records
- Control category and type
- Implementation status (Implemented / Partial / Missing)
- Risk priority score (1–10 visual meter)
- Compliance framework mapping (PCI-DSS / SOC 2)
- Reasoning for placement
- Why it matters specifically for NovaPay
- Recommended remediation action

---

## 🖥️ Dashboard Features

- **7 interactive tabs** — Company Profile, Technical, Managerial, Operational, Physical, Gap Analysis, Executive Summary
- **Filter & search** — filter controls by status or type, live search across all controls
- **Expandable rows** — click any control to reveal reasoning, placement justification, and action items
- **Risk score meters** — visual 1–10 priority bars for every control
- **Progress rings** — per-category coverage percentage that animates on load
- **Donut & bar charts** — gap analysis visualizations built with Chart.js
- **Dynamic stats bar** — total, implemented, partial, and missing counts calculated live from data
- **Executive Summary tab** — one-page CISO-ready brief with print-to-PDF export
- **Company Profile tab** — full NovaPay backstory, team structure, tech stack, and threat landscape
- **Compliance tagging** — PCI-DSS and SOC 2 tags on every applicable control

---

## 🔍 Key Findings (Gap Analysis)

After mapping all controls, the analysis identified three critical gaps for NovaPay:

1. **No Manual Transaction Review process** — the only Compensating control is Missing, creating direct PCI-DSS Requirement 10 exposure
2. **IR Plan never exercised** — a documented plan without tabletop practice is insufficient for a payment processor
3. **No Privileged Access Management (PAM)** — AWS admin accounts without session recording or approval workflows represent an unchecked insider threat vector

The weakest control *type* across all categories is **Compensating**, followed by **Deterrent** — both underrepresented relative to NovaPay's threat landscape.

---

## 📁 Files

| File | Description |
|---|---|
| `novapay_security_dashboard_v3.html` | Main interactive dashboard (open in any browser) |
| `CompTIA_Project_1.xlsx` | Source spreadsheet with all control data |
| `README.md` | This file |

---

## 🧠 CompTIA Security+ Concepts Demonstrated

- Security control categories (Technical, Managerial, Operational, Physical)
- Security control types (Preventive, Detective, Corrective, Deterrent, Compensating, Directive)
- Gap analysis methodology
- Risk assessment and prioritization
- PCI-DSS and SOC 2 compliance frameworks
- Threat modeling for a fintech environment
- Executive security reporting (CISO communication)

---

## 🚀 How to View

**Option 1 — Live (GitHub Pages):**
Visit the link above once GitHub Pages is enabled.

**Option 2 — Local:**
1. Download `novapay_security_dashboard_v3.html`
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. No installation or dependencies required

---

## 👤 Author

**Rei Zaimi**
Security Analyst | CompTIA Security+ Candidate
[GitHub](https://github.com/yourusername) · [LinkedIn](https://linkedin.com/in/yourprofile)

---

*This project was built as part of a self-directed CompTIA Security+ study program. NovaPay Inc. is entirely fictional and was created using AI assistance for educational purposes. No real company, data, or individuals are represented.*
