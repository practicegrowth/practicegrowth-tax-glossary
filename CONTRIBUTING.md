# Contributing to PracticeGrowth Tax Terms Glossary

## Overview

This is an open-source tax glossary maintained by **[PracticeGrowth.Tech](https://www.PracticeGrowth.tech)**. We welcome contributions that improve accuracy, expand coverage, or enhance clarity.

## Scope

We accept terms related to:

- **US Federal taxation** (IRS code, regulations, publications)
- **State-level taxation** (major states, especially Texas and CPA-relevant jurisdictions)
- **CPA/Accounting practice terminology** (commonly encountered in client-facing situations)
- **Tax credit and deduction terminology**
- **Entity structuring for tax purposes** (S-Corp, LLC, Partnership, etc.)

We currently do NOT accept:

- Non-US tax definitions (other than cross-border/international provisions like FATCA, FBAR, PFIC, GILTI)
- Corporate law unrelated to tax implications
- Financial planning beyond direct tax effects

## How to Contribute

### 1. Report Issues

Open a GitHub issue if you find:

- ❌ Incorrect or outdated definitions
- 🔤 Missing terms important to tax professionals
- 🔄 Duplicate entries that should be merged
- 💡 Suggestions to improve clarity or context

### 2. Submit Corrections

For minor corrections (typos, small updates):

1. Fork this repository
2. Edit the appropriate `terms/X-Y.md` file
3. Submit a Pull Request with your changes

### 3. Adding New Entries

When adding new terms, follow these conventions:

```markdown
### Term Name
*Sources (N): Source Name; Source Name*

Clear, concise definition. Keep it accurate and complete. No truncation.

**Additional context from other sources:**

> Definition from another source providing supplementary perspective.
---
```

**Formatting rules:**

- Use `###` (H3) for each term heading
- Include source attribution with count and human-readable source names
- Preserve full definitions — no summarization or shortening
- If multiple sources contribute, use the most authoritative as primary
- End every entry with `---\n\n` separator

**Source reference table:**

| Key | Display Name |
|-----|-------------|
| irs_vita | IRS VITA Glossary |
| irs_student | IRS Understanding Taxes Student Glossary |
| turbotax | TurboTax/Intuit Tax Terms Glossary |
| thomson_reuters | Thomson Reuters Tax Glossary |
| taxgpt | TaxGPT Tax Glossary |
| bluewatertax | Blue Water Tax Glossary |
| htj_tax | HTJ Tax American Tax Glossary |
| taxdefense | Tax Defense Network Tax Definitions |
| mytaxrights | MyTaxRights.org Tax Glossary |
| npbctax | NPBC Tax Glossary |
| taxpolicycenter | Tax Policy Center Briefing Book |
| taxfoundation | Tax Foundation TaxEDU Glossary |
| instead | Instead.com Tax Glossary |
| vermont | Vermont Department of Taxes Glossary |
| msu_law | MSU Law Tax Clinic Glossary |
| tax1099 | Tax1099.com Glossary |
| taxdome | TaxDome Glossary |
| github_legacy | PracticeGrowth Tax Glossary (curated) |

## Quality Standards

Before submitting:

1. ✅ Verify the definition against the original source
2. ✅ Ensure alphabetical placement is correct
3. ✅ Confirm source attribution matches the definition used
4. ✅ Check that no duplicate exists in nearby letter ranges
5. ✅ Review existing entries for consistency in tone and format

## Structure

```
practicegrowth-tax-glossary/
├── README.md              # Project overview
├── _all-terms.json         # Machine-readable index (1,131 terms)
├── CONTRIBUTING.md         # This file
└── terms/                  # Alphabetically chunked files
    ├── A-C.md              # 209 terms
    ├── D-F.md              # 211 terms
    ├── G-I.md              # 97 terms
    ├── J-L.md              # 36 terms
    ├── M-O.md              # 84 terms
    ├── P-R.md              # 102 terms
    ├── S-U.md              # 176 terms
    └── V-Z.md              # 216 terms
```

## Questions?

Open a GitHub issue labeled `question` or contact us at hello@practicegrowth.tech

---

*Maintained by PracticeGrowth.Tech — https://www.PracticeGrowth.tech*
