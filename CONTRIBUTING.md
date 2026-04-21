# Contributing to PSB CISO Quantum Readiness Diagnostic

Thank you for your interest in contributing. This tool is built for India's public sector banking community and benefits from input by cybersecurity professionals, policy researchers, and banking technologists.

---

## How to Contribute

### 1. Reporting Issues
If you find a bug, scoring error, or outdated regulatory reference:
- Open a **GitHub Issue**
- Include: what you expected, what happened, and which browser/device you used

### 2. Suggesting Updates
Regulatory frameworks evolve. If a new RBI circular, CERT-In advisory, or NQM update affects any checklist item:
- Open an Issue with the title: `[Update] <area name>`
- Paste the relevant source or notification
- Suggest the revised action item text

### 3. Submitting a Pull Request
```bash
# Fork the repo, then:
git clone https://github.com/yourusername/psb-quantum-diagnostic.git
git checkout -b your-feature-branch

# Make your changes to index.html
# Test in Chrome, Firefox, and Safari before submitting

git commit -m "Brief description of change"
git push origin your-feature-branch
# Then open a Pull Request on GitHub
```

---

## What We Welcome

- **Regulatory updates** — new RBI IT guidelines, CERT-In advisories, NQM milestones
- **New checklist areas** — cloud-specific PQC, UPI/NPCI quantum readiness, CBDC security
- **Translations** — Hindi or regional language versions for wider PSB reach
- **Accessibility improvements** — keyboard navigation, screen reader support, contrast fixes
- **Print/export enhancements** — better PDF layout, Word export option

## What to Avoid

- Changing the scoring model (2.5 pts per action item) without a detailed rationale in the PR
- Adding external JavaScript libraries or framework dependencies — the tool must remain a single self-contained HTML file
- Removing the regulatory framework attributions in the footer

---

## Code Style

- The entire tool lives in **one HTML file** (`index.html`) — keep it that way
- CSS uses **CSS custom properties** (variables) for all colours — add new colours as variables, not inline hex
- JavaScript is vanilla ES6 — no jQuery, no frameworks
- Keep the dark theme consistent with the existing design system

---

## Attribution

Contributors will be acknowledged in the CHANGELOG. If you make a significant contribution (new checklist area, major regulatory update), feel free to add yourself to the README's contributors section in your PR.

---

*Questions? Open a GitHub Issue or reach out via the Medium article linked in the README.*
