# Contributing to PracticeGrowth Tax Terms Glossary

## Overview

This is an open-source tax glossary maintained by **[PracticeGrowth.Tech](https://practicegrowth.tech)**. We welcome contributions that improve accuracy, expand coverage, or enhance clarity.

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

*Source: **Source Name***

Clear, concise definition. Keep it accurate and complete. No truncation.

**Additional context:**

> Definition from another source providing supplementary perspective.
---
```

**Formatting rules:**

- Use `###` (H3) for each term heading
- Include at least one source attribution per term
- Preserve full definitions — no summarization or shortening
- If multiple sources contribute, use the most authoritative as primary
- End every entry with `---\n\n` separator

**Source name abbreviations:**

| Source | Display Name |
|--------|-------------|
| irs_vita | IRS VITA Courseware |
| irs_student | IRS Student Guide |
| turbotax | TurboTax Intuit |
| thomson_reuters | Thomson Reuters |
| taxgpt | TaxGPT |
| bluewatertax | Blue Water Tax |
| htj_tax | HTJ Tax |
| taxdefense | Tax Defense Network |
| mytaxrights | MyTaxRights.org |
| npbctax | NPBC Accounting & Tax |
| taxpolicycenter | Tax Policy Center |
| taxfoundation | Tax Foundation |
| instead | Instead |
| vermont | VT Dept of Taxes |
| msu_law | MSU Law Clinic |
| tax1099 | Tax1099 |
| taxdome | TaxDome |

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
├── _all-terms.json         # Machine-readable index
├── CONTRIBUTING.md         # This file
└── terms/                  # Alphabetically chunked files
    ├── A-C.md              # ~175 terms
    ├── D-F.md              # ~298 terms
    ├── G-I.md              # ~93 terms
    ├── J-L.md              # ~35 terms
    ├── M-O.md              # ~91 terms
    ├── P-R.md              # ~127 terms
    ├── S-U.md              # ~166 terms
    └── V-Z.md              # ~40 terms
```

## Questions?

Open a GitHub issue labeled `question` or contact us at hello@practicegrowth.tech

---

*Maintained by PracticeGrowth.Tech — https://practicegrowth.tech*
