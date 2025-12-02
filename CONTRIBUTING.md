# Contributing to ImpactLex

Thank you for your interest in improving ImpactLex! This dictionary serves development practitioners, researchers, and students across South Asia and beyond. Your contributions help make development knowledge more accessible.

---

## Ways to Contribute

### 📖 Add New Terms
We welcome new glossary entries in these categories:
- MEAL (Monitoring, Evaluation, Accountability & Learning)
- Theory of Change
- Gender & Social Inclusion
- Research Methods
- Development Economics
- Governance & Accountability
- Climate & Environment

### 📐 Add Formulae
Mathematical and statistical formulae used in development practice, with clear explanations.

### 📋 Add Case Studies
Real-world examples of development concepts in action, with citations.

### 🌐 Translations
Help translate terms into Hindi, Tamil, Bengali, Telugu, Marathi, or other South Asian languages.

### 🐛 Report Issues
Found an error? Definition unclear? Broken link? Open an issue!

---

## Quality Standards

### For Glossary Terms

All terms must include:

| Field | Requirement |
|-------|-------------|
| **Definition** | Rigorous, accurate, 2-4 sentences minimum |
| **Sources** | At least 1 authoritative citation |
| **Category** | Assigned to appropriate category |
| **Related Terms** | 2-5 connected concepts |

**Authoritative Sources:**
- OECD-DAC Evaluation Criteria
- UNDP, World Bank, UN agencies
- J-PAL, IPA, 3ie
- Peer-reviewed academic publications
- Government statistical agencies

**Avoid:**
- Wikipedia (use original sources instead)
- Blog posts or opinion pieces
- Uncited definitions
- Marketing materials

### For Formulae

Must include:
- Formula name
- Mathematical expression
- Plain-language explanation
- Variable definitions
- At least one source

### For Case Studies

Must include:
- Programme/study name
- Country and year
- Published evaluation source
- Key finding with evidence
- Lessons learned

---

## How to Submit

### Option 1: GitHub Pull Request (Preferred)

1. **Fork** this repository
2. **Edit** `index.html` and find the relevant data array:
   - `GLOSSARY_DATA` for terms
   - `FORMULAE_DATA` for formulae
   - `CASE_STUDIES_DATA` for case studies
3. **Add** your entry following the existing format
4. **Test** locally to ensure it renders correctly
5. **Submit** a pull request with a clear description

### Option 2: Open an Issue

If you're not comfortable with code:
1. Open a new issue
2. Use the title format: `[New Term] Term Name` or `[Correction] Term Name`
3. Provide all required information
4. We'll add it for you!

### Option 3: Email

Send contributions to: **hello@impactmojo.in**

---

## Term Entry Format

```javascript
{
    id: 'unique-id',           // lowercase, hyphenated
    term: 'Term Name',         // Title case
    acronym: 'ABC',            // or null if none
    category: 'meal',          // one of: meal, toc, gender, research, economics, governance, climate
    definition: 'Your rigorous definition here...',
    formula: null,             // or formula object (see below)
    caseStudy: null,           // or case study object (see below)
    relatedTerms: ['Term 1', 'Term 2', 'Term 3'],
    sources: ['Author (Year)', 'Organization Report']
}
```

### Formula Object Format

```javascript
formula: {
    name: 'Formula Name',
    expression: 'Y = a + bX',
    explanation: 'Plain language explanation...',
    variables: [
        { symbol: 'Y', meaning: 'Description' },
        { symbol: 'X', meaning: 'Description' }
    ]
}
```

### Case Study Object Format

```javascript
caseStudy: {
    title: 'Programme or Study Name',
    region: 'South Asia',      // or: Africa, Latin America, Global
    year: 2020,
    summary: 'Brief description of the case...',
    keyFinding: 'Main evidence or lesson...'
}
```

---

## Code of Conduct

- Be respectful and constructive
- Focus on accuracy and evidence
- Credit original sources
- Welcome contributors of all backgrounds
- Keep discussions professional

---

## Recognition

All contributors will be acknowledged in our release notes. Significant contributors may be invited to join as maintainers.

---

## Questions?

- **Email:** hello@impactmojo.in
- **Website:** [impactmojo.in](https://impactmojo.in)

---

**Thank you for helping make development knowledge accessible to all! 💜**
