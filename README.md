# ImpactLex

**Development Sector Terminology Dictionary with Formulae and Case Studies**

[![Netlify Status](https://api.netlify.com/api/v1/badges/your-badge-id/deploy-status)](https://impactlex.impactmojo.in)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

ImpactLex is a free, offline-capable Progressive Web App (PWA) providing rigorous definitions of development sector terminology. Built for NGO professionals, impact practitioners, researchers, and students across South Asia and beyond.

**[🚀 Launch ImpactLex](https://impactlex.impactmojo.in)** · **[📚 ImpactMojo](https://impactmojo.in)**

---

## Features

| Feature | Description |
|---------|-------------|
| 📖 **Glossary** | 200+ terms with rigorous definitions from OECD-DAC, UNDP, World Bank, J-PAL |
| 📐 **Formulae** | Key equations used in impact evaluation and development economics |
| 📋 **Case Studies** | Real-world applications from Progresa to BRAC Graduation |
| 🔍 **Smart Search** | Fuzzy matching across terms, definitions, and acronyms |
| 🏷️ **Categories** | MEAL, Theory of Change, Gender, Research Methods, Economics, Governance, Climate |
| 🌙 **Dark Mode** | Comfortable reading in any environment |
| 📱 **PWA** | Install on mobile/desktop, works offline |
| 💾 **Bookmarks** | Save terms with CSV export |

---

## Categories

- **MEAL** — Monitoring, Evaluation, Accountability & Learning
- **Theory of Change** — Programme design and causal pathways
- **Gender** — Intersectionality, GBA+, unpaid care, mainstreaming
- **Research Methods** — RCTs, DiD, PSM, quasi-experimental designs
- **Development Economics** — Poverty measurement, inequality, cost-effectiveness
- **Governance** — Accountability, participation, decentralization
- **Climate** — Adaptation, mitigation, resilience, NDCs

---

## Getting Started

### Use Online
Visit **[impactlex.impactmojo.in](https://impactlex.impactmojo.in)**

### Install as App
1. Open the site on your phone or desktop browser
2. Click "Install" when prompted (or use browser menu → "Add to Home Screen")
3. Access offline anytime

### Run Locally
```bash
git clone https://github.com/yourusername/impactlex.git
cd impactlex
# Serve with any static server
python -m http.server 8000
# or
npx serve
```

---

## Project Structure

```
impactlex/
├── index.html      # Main application (single-page app)
├── manifest.json   # PWA manifest for installation
├── sw.js           # Service worker for offline functionality
├── README.md
├── LICENSE
└── .gitignore
```

---

## Data Sources

Definitions are sourced from authoritative references including:

- **OECD-DAC** Evaluation Criteria and Glossary
- **UNDP** Results-Based Management Handbook
- **World Bank** Development Impact Evaluation (DIME)
- **J-PAL** Research Resources
- **UN Women** Gender Equality Glossary
- **IPCC** Climate Assessment Reports
- Academic literature (Sen, Banerjee, Duflo, Angrist, etc.)

---

## Contributing

We welcome contributions! To add or improve terms:

1. Fork the repository
2. Edit the `GLOSSARY_DATA`, `FORMULAE_DATA`, or `CASE_STUDIES_DATA` arrays in `index.html`
3. Ensure definitions cite authoritative sources
4. Submit a pull request

**Quality Standards:**
- Definitions must be rigorous and source-backed
- Formulae must include variable explanations
- Case studies must cite published evaluations

---

## Part of ImpactMojo

ImpactLex is part of the **[ImpactMojo](https://impactmojo.in)** ecosystem — a free educational platform for development sector professionals offering:

- 📚 Courses in MEAL, Theory of Change, Gender, Research Methods
- 🧪 Interactive Labs and Tools
- 🎓 Coaching and Workshops
- 🌏 Content in English, Hindi, Tamil, Bengali, Telugu, Marathi

---

## License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

You are free to:
- **Share** — copy and redistribute the material
- **Adapt** — remix, transform, and build upon the material

Under the following terms:
- **Attribution** — Credit ImpactMojo and link to the original
- **NonCommercial** — Not for commercial purposes
- **ShareAlike** — Distribute contributions under the same license

---

## Contact

- **Website:** [impactmojo.in](https://impactmojo.in)
- **Email:** hello@impactmojo.in
- **LinkedIn:** [ImpactMojo](https://linkedin.com/company/impactmojo)

---

<p align="center">
  <strong>Built with 💜 for the development sector</strong><br>
  <sub>© 2024 ImpactMojo. All rights reserved.</sub>
</p>
