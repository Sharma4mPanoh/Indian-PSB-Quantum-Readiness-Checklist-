# 🔐 PSB CISO Quantum Readiness Diagnostic

> An interactive, browser-based diagnostic tool for Chief Information Security Officers at India's Public Sector Banks — built to assess quantum encryption readiness against the Finance Ministry's mandate and India's National Quantum Mission (NQM).

[![License: MIT](https://img.shields.io/badge/License-MIT-cyan.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Version-2.0-blue.svg)]()
[![Status](https://img.shields.io/badge/Status-Live-brightgreen.svg)]()
[![Framework](https://img.shields.io/badge/Framework-NQM%20%7C%20NIST%20PQC%20%7C%20CERT--In-orange.svg)]()

---

## 🖥️ Live Demo

👉 **[Launch the Diagnostic Tool](https://yourusername.github.io/psb-quantum-diagnostic/)**

> Replace the link above with your actual GitHub Pages URL after publishing.

---

## 📋 What Is This?

India's Finance Ministry has directed all Public Sector Banks (PSBs) to explore quantum-resistant encryption. With Q-Day — the point at which quantum computers can break current cryptography — projected as early as 2029, PSBs face a narrow and urgent window to act.

This diagnostic tool helps a CISO:

- Understand **where their bank currently stands** across 10 critical quantum readiness areas
- Mark each of **40 granular action items** as *Not Started* or *Started*
- Get an **instant readiness score out of 100** with category-level breakdowns
- Identify the **highest-priority gaps** to address first
- Generate a **shareable score report** for board or regulator briefings

---

## 🎯 How It Works

The diagnostic covers **10 quantum readiness areas**, each containing **4 actionable items**:

| # | Area | Priority | Category |
|---|------|----------|----------|
| 01 | Cryptographic Inventory & Audit | 🔴 Critical | Governance |
| 02 | Harvest Now, Decrypt Later (HNDL) Exposure | 🔴 Critical | Governance |
| 03 | NIST PQC Algorithm Adoption | 🔴 Critical | Technical |
| 04 | RBI / CERT-In / NQM Compliance Mapping | 🔴 Critical | Governance |
| 05 | Vendor & Third-Party PQC Readiness | 🟠 High | Technical |
| 06 | Cryptographic Agility Architecture | 🟠 High | Technical |
| 07 | Quantum Key Distribution (QKD) Evaluation | 🟠 High | Operations |
| 08 | Legacy System Migration Roadmap | 🟠 High | Technical |
| 09 | PQC Talent & Awareness Development | 🔵 Medium | Operations |
| 10 | Board-Level Quantum Risk Reporting | 🔵 Medium | Operations |

### Scoring

Each action item marked **Started = 2.5 points**. Not Started = 0 points.

```
40 action items × 2.5 points = 100 points maximum
```

| Score Range | Readiness Level |
|-------------|----------------|
| 0 – 20 | 🔴 Critical Risk |
| 21 – 40 | 🟠 High Risk |
| 41 – 60 | 🟡 Moderate Risk |
| 61 – 80 | 🔵 Progressing |
| 81 – 100 | 🟢 Quantum Ready |

Category scores are tracked separately: **Governance (30 pts) · Technical (40 pts) · Operations (30 pts)**

---

## 🚀 Usage

### Option A — Use the Live Version
Click the GitHub Pages link above. No installation required. Runs entirely in the browser.

### Option B — Run Locally
```bash
# Clone the repository
git clone https://github.com/yourusername/psb-quantum-diagnostic.git

# Open in browser
open index.html
# or double-click index.html in your file explorer
```

### Option C — Embed in Your Own Site
Download `index.html` and host it on any static web server or CMS. The file has zero external dependencies beyond Google Fonts.

---

## ✨ Features

- **Zero dependencies** — pure HTML, CSS, and vanilla JavaScript. No frameworks, no build step.
- **Live scoring** — score updates instantly as you toggle each action item.
- **Animated ring gauge** — visual readiness indicator with colour-coded tiers.
- **Category breakdown** — separate progress bars for Governance, Technical, and Operations.
- **Per-item mini progress** — each area header shows how many of its 4 action items are started.
- **Print / Save PDF** — clean print stylesheet for offline sharing or board presentations.
- **Copy Score Report** — exports a full itemised summary to clipboard for emails or audit documentation.
- **Reset** — clear all responses and start fresh.
- **Mobile responsive** — works on phones and tablets.

---

## 📐 Regulatory & Framework Alignment

This diagnostic is built on the following frameworks and directives:

- **Finance Ministry PSB Directive** — quantum-resistant encryption mandate for Public Sector Banks
- **NIST FIPS 203** (ML-KEM), **FIPS 204** (ML-DSA), **FIPS 205** (SLH-DSA) — August 2024 PQC standards
- **NIST HQC** — additional key encapsulation mechanism selected March 2025
- **CERT-In & SISA Quantum Cyber Readiness Whitepaper** — July 2025
- **India National Quantum Mission (NQM)** — ₹6,003.65 crore national initiative
- **MeitY 2025 Whitepaper** — "Transitioning to Quantum Cyber Readiness"
- **Government Task Force Report** — Implementation of Quantum Safe Ecosystem in India (February 2026)
- **PSB Hackathon 2026** — PNB / IIT Kanpur initiative on quantum-proof banking systems
- **IBA Working Groups** — Indian Banks' Association quantum cybersecurity standards

---

## 🗂️ Repository Structure

```
psb-quantum-diagnostic/
│
├── index.html          # The complete diagnostic tool (single file)
├── README.md           # This file
├── CHANGELOG.md        # Version history
├── CONTRIBUTING.md     # How to contribute
└── LICENSE             # MIT License
```

---

## 🤝 Contributing

Contributions are welcome — especially from cybersecurity professionals, banking technologists, and policy researchers in India. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

Areas where contributions are most valuable:
- Updating action items as new RBI/CERT-In guidelines are issued
- Adding new checklist areas (e.g., cloud-specific PQC, UPI security)
- Translations into Hindi or regional languages for wider PSB reach
- Accessibility improvements

---

## 📰 Background Reading

This tool was built to accompany the Medium article:

> **"India's Public Banks Are Running Out of Time: The ₹2,000 Crore Quantum Encryption Race That Could Decide the Future of Your Money"**

---

## 📄 License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.

Free to use, share, fork, and adapt. Attribution appreciated but not required.

---

## ⚠️ Disclaimer

This diagnostic is an educational and self-assessment tool. It does not constitute regulatory advice, a formal security audit, or compliance certification. Banks should engage qualified cybersecurity professionals and refer to official RBI, CERT-In, and NQM guidelines for formal compliance obligations.

---

*Built for Indian PSB CISOs · Version 2.0 · April 2026*
