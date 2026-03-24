# ImpactLex

[![Netlify Status](https://api.netlify.com/api/v1/badges/4f33bcdf-dd5c-4cfc-ba82-2a91ca0b4753/deploy-status)](https://app.netlify.com/projects/impactlex/deploys)
[![Website](https://img.shields.io/badge/Website-impactlex.impactmojo.in-7C3AED)](https://impactlex.impactmojo.in)
[![PWA](https://img.shields.io/badge/PWA-Offline--Capable-brightgreen)](https://impactlex.impactmojo.in)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/Content-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![License: MIT](https://img.shields.io/badge/Code-MIT-green.svg)](LICENSE)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/Varnasr/ImpactLex)](https://github.com/Varnasr/ImpactLex/commits/main)
[![Part of ImpactMojo](https://img.shields.io/badge/Part%20of-ImpactMojo-orange)](https://www.impactmojo.in)

**A free, offline-capable Progressive Web App providing rigorous definitions of 500+ development sector terms — with formulae, case studies, and real-world applications.**

Built for NGO professionals, impact practitioners, researchers, and students across South Asia and beyond.

**[Launch ImpactLex](https://impactlex.impactmojo.in)** · **[ImpactMojo Platform](https://impactmojo.in)**

---

## About

ImpactLex addresses a recurring problem in development work: the same term means different things to different people. MEAL practitioners, economists, gender specialists, and communications professionals all use overlapping vocabulary with subtly different meanings — leading to misaligned programmes, poorly designed evaluations, and avoidable disagreements.

ImpactLex provides a single, authoritative, open-access reference grounded in international standards (OECD-DAC, UNDP, World Bank, J-PAL) and contextualised for South Asian practice.

---

## Features

| Feature | Description |
|---------|-------------|
| **500+ Terms** | Rigorous definitions sourced from OECD-DAC, UNDP, World Bank, J-PAL, and peer-reviewed literature |
| **Domain Coverage** | MEAL, Theory of Change, Gender Studies, Research Methods, Development Economics |
| **Mathematical Formulae** | Key equations for impact evaluation, sampling, cost-effectiveness, and econometrics |
| **Case Studies** | Real-world applications — from Progresa to BRAC Graduation to Right to Information |
| **Full-Text Search** | Instant search across all terms, definitions, and case studies |
| **Category Filters** | Browse by domain, method type, or complexity level |
| **Offline-Capable PWA** | Installable on any device — works without internet access once cached |
| **Dark Mode** | Full dark mode with persistent preference (localStorage) |
| **Zero Dependencies** | Vanilla HTML/CSS/JS — no framework, no build step |

---

## Domain Coverage

| Domain | Example Terms |
|--------|--------------|
| **MEAL** | Theory of Change, Logframe, DACS criteria, contribution analysis, utilisation-focused evaluation |
| **Research Methods** | RCT, quasi-experimental design, propensity score matching, regression discontinuity, ANOVA |
| **Development Economics** | Elasticity, Gini coefficient, multidimensional poverty, social protection, fiscal multiplier |
| **Gender Studies** | Gender mainstreaming, care economy, intersectionality, gender-responsive budgeting |
| **Impact Evaluation** | Attribution, counterfactual, MDE, ITT, LATE, spillovers, external validity |

---

## Architecture

ImpactLex is a single-page Progressive Web App:

```
ImpactLex/
├── index.html          # Complete app (HTML + CSS + JS, single file)
├── manifest.json       # PWA manifest (installable, offline-capable)
├── sw.js               # Service Worker (offline caching)
├── icons/              # App icons for all device sizes
├── LICENSE
└── README.md
```

The entire dictionary is embedded in the HTML file as a JavaScript data structure — no external API calls, no server required, fully functional offline.

---

## PWA Installation

On Chrome/Edge:
1. Visit [impactlex.impactmojo.in](https://impactlex.impactmojo.in)
2. Click the install icon in the address bar (or menu → "Install app")
3. ImpactLex will be available on your home screen, works offline

On iOS (Safari):
1. Tap the Share button
2. Select "Add to Home Screen"

---

## Tech Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| Frontend | Vanilla HTML / CSS / JavaScript | Single-page dictionary app |
| PWA | Service Worker + Web App Manifest | Offline capability and installability |
| Hosting | Netlify | CDN, auto-deploy from GitHub |
| Domain | impactlex.impactmojo.in | Subdomain via Netlify DNS |

---

## Local Development

```bash
git clone https://github.com/Varnasr/ImpactLex.git
cd ImpactLex

# Open directly
open index.html

# Or serve (required for PWA features like Service Worker)
python3 -m http.server 8000
# then visit http://localhost:8000
```

> Note: Service Workers require a secure context (HTTPS or localhost). Use a local server rather than opening the file directly to test PWA features.

---

## Contributing

Contributions welcome — new terms, improved definitions, additional case studies, or corrections.

**Guidelines:**
- Definitions should cite a primary source (OECD-DAC, J-PAL, World Bank, peer-reviewed paper)
- Formulae should be rendered in LaTeX notation within the definition
- Case studies should reference a real programme with a verifiable evaluation

Open a pull request or [file an issue](https://github.com/Varnasr/ImpactLex/issues).

---

## Part of the ImpactMojo Ecosystem

**Related repositories:**
- [ImpactMojo](https://github.com/Varnasr/ImpactMojo) — Main platform
- [dev-case-studies](https://github.com/Varnasr/dev-case-studies) — 200 real development case studies
- [development-discourses](https://github.com/Varnasr/development-discourses) — 500+ curated open-access papers
- [InsightStack](https://github.com/Varnasr/InsightStack) — MEL tools and calculators

---

## License

- **Content (definitions, formulae, case studies):** CC BY-NC-SA 4.0
- **Code:** MIT

---

## Citation

```
Sri Raman, V. (2025). ImpactLex: Development Sector Terminology Dictionary [Software].
ImpactMojo. https://impactlex.impactmojo.in
```
