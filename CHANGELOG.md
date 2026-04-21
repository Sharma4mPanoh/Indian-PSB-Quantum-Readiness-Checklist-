# Changelog

All notable changes to the PSB CISO Quantum Readiness Diagnostic will be documented here.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [2.0] — April 2026

### Changed
- **Scoring model overhauled** — score now based on 40 granular action items (2.5 pts each) instead of 10 top-level checkboxes
- Each action item now has a **Not Started / Started toggle pill** replacing the single item checkbox
- Item headers now show a live **"X / 4 started"** mini-counter and progress bar

### Added
- Scoring key panel explaining the 2.5 pts per action item model
- Per-item colour state: amber (partially started), green (all started)
- Sub-item rows highlight green background when marked Started
- Copy Score Report now exports full itemised breakdown including sub-item status

### Removed
- Top-level item checkbox (replaced by sub-item toggles)

---

## [1.0] — April 2026

### Added
- Initial release with 10 checklist items and single checkbox per item
- Animated ring gauge score display (0–100)
- Five readiness tiers: Critical Risk → Quantum Ready
- Category breakdown: Governance / Technical / Operations
- Print / Save PDF support with clean print stylesheet
- Copy Score Summary to clipboard
- Reset All function
- Mobile responsive layout
- Fixed global progress bar
- Dark command-centre aesthetic with grid overlay

---

*Maintained by the repository author. Contributions welcome via pull request.*
