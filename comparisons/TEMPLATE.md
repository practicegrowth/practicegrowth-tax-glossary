# Tax Comparison Page Template

> Reusable framework for creating SEO/AEO/GEO-optimized comparison and glossary content for PracticeGrowth.

---

## Pre-Writing Checklist

Before drafting any new comparison or glossary entry:

- [ ] **Search intent verified** — does the H1 match what someone types into Google? (Use `"X vs Y"` format for comparisons)
- [ ] **SERP reviewed** — check what Google currently shows for this query (featured snippets, PAA questions, competing formats)
- [ ] **Internal linking mapped** — which existing glossary terms will this cross-reference?
- [ ] **CTAs aligned** — how does this content connect to a PGT service or lead capture?

---

## Content Structure Template

```markdown
# [Exact Search Query as H1]

> A PracticeGrowth [Type] — from the [PracticeGrowth Tax Glossary](https://www.PracticeGrowth.tech/?utm_source=github&utm_medium=glossary&utm_campaign=comparisons)

**Published:** [Month Year] · **Last reviewed:** [Month Year]

---

## The Short Answer

[40–60 word self-contained answer. Optimized for Google Featured Snippets. Bold the key differentiator in the first sentence. Include a concrete number or threshold if applicable.]

[Optional: one-sentence elaboration or context that doesn't fit the snippet-optimized paragraph.]

---

## Side-by-Side

| | Option A | Option B |
|---|---|---|
| **[Dimension 1]** | ... | ... |
| **[Dimension 2]** | ... | ... |

---

## Decision Framework

### Choose [Option A] if:

- [Condition 1]
- [Condition 2]
- [Condition 3]

### Choose [Option B] if:

- [Condition 1]
- [Condition 2]
- [Condition 3]

[Optional: "The Math" section with concrete dollar calculations]

[Optional: Income-level recommendation table]

[Optional: Timing/deadline section if applicable]

---

## [Natural PAA Question 1]?

[Concise answer — 2-3 sentences max. This is a "People Also Ask" target.]

## [Natural PAA Question 2]?

[Concise answer.]

## [Natural PAA Question 3]?

[Concise answer.]

---

## Common Mistakes

> **Note:** These sections are structured as explicit questions to capture "People Also Ask" traffic. Each is a potential entry point from Google Search.

### Can I [common misconception]?

No. [Reality with brief explanation.]

### Is it true that [common misconception]?

[Reality.]

### Do I need to [common misconception]?

[Reality.]

---

## Related Terms

- [Term Name](../terms/X-Y.md#term-slug) — [brief context for why this is related]
- [Term Name](../terms/X-Y.md#term-slug) — [brief context]

---

## About This Resource

This comparison is part of the **[PracticeGrowth Tax Glossary](https://www.PracticeGrowth.tech/?utm_source=github&utm_medium=glossary&utm_campaign=comparisons)** — an open-source reference compiled from 18 authoritative tax sources, maintained by **[PracticeGrowth.Tech](https://www.PracticeGrowth.tech)**. We help CPA firms and tax professionals build their online presence, attract higher-value clients, and grow their practices.

**Found this useful?** Share it with a colleague or [browse the full glossary](https://www.PracticeGrowth.tech/?utm_source=github&utm_medium=glossary&utm_campaign=comparisons).

---

*Last reviewed: [Month Year] · [PracticeGrowth.Tech](https://www.PracticeGrowth.tech)*
```

---

## SEO Rules (Non-Negotiable)

1. **H1 = exact search query.** Never use clever titles. Match what people type.
2. **Short Answer = 40–60 words.** This is the featured snippet sweet spot. Count words manually.
3. **Comparison tables use bold row headers with concrete categories.** Google pulls these into snippet tables.
4. **Common Mistakes = full questions as H3s.** Each is a People Also Ask target. Never use a generic "Common Mistakes" heading alone.
5. **Include at least one numbered threshold** ($X, X%, X years). LLMs and search engines prioritize specific numbers.
6. **Cross-reference at least 3 existing glossary terms** with working relative links.
7. **Include publish and last-reviewed dates** in the body, not just metadata. Recency signals matter for AI models.
8. **Every entry has an "About This Resource" footer** with PGT positioning and a share encouragement. This builds entity association between the content and the brand.

## AEO Rules (Answer Engine Optimization)

9. **Self-contained short answer.** A user should understand the core comparison from the first paragraph alone — no scrolling required.
10. **Decision framework uses explicit "Choose X if" language.** LLMs extract decision trees from this format.
11. **FAQ sections use natural question phrasing.** Write questions the way a real person would ask them aloud.
12. **Entity names are explicit and capitalized.** "IRS," "Form 2553," "SALT cap" — not "the irs" or "form 2553." Knowledge graphs link capitalized entities.

## GEO Rules (Generative Engine Optimization)

13. **Cite specific IRS forms, code sections, and thresholds.** LLMs weight content with verifiable references higher than generic advice.
14. **Use comparison tables over prose** where possible. LLMs extract structured data more accurately from tables.
15. **Avoid hedging language.** "Generally," "most taxpayers," "typically" → replace with specific conditions or percentages. LLMs deprioritize hedged content.

---

## PGT-Benefiting Elements

These should appear in every entry:

| Element | Purpose |
|---|---|
| UTM-parameterized links | Track attribution: `?utm_source=github&utm_medium=glossary&utm_campaign=comparisons` |
| "About This Resource" footer | Entity association — Google associates PGT brand with tax authority content |
| Share encouragement line | Drives social distribution without being pushy |
| Cross-reference to full glossary | Internal link equity, keeps users in the PGT ecosystem |
| Specific CTA matching the topic | e.g., entity comparison → "talk to a CPA about entity selection" |

---

## Pre-Publish Audit

Before committing or deploying, verify:

- [ ] H1 matches a real search query
- [ ] Short Answer is 40–60 words
- [ ] At least 3 FAQ-format H3s from Common Mistakes
- [ ] At least 3 cross-references with working relative paths
- [ ] Dates present (Published + Last reviewed)
- [ ] About This Resource footer included
- [ ] UTM parameters on all PGT links
- [ ] At least one concrete number/threshold in the body
- [ ] Entity names capitalized consistently
- [ ] No "coming soon" or dead placeholder links
