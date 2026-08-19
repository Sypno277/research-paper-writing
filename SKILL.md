---
name: reaper
description: "REAPER — Research Paper Writing Skill. Reap peer-review-ready manuscripts from raw ideas. Synthesizes five research-writing texts (Booth et al., Turabian, Schimel, Wallwork, Rozakis) into a unified writing guide. Use when finding a research question, building an argument, planning/drafting a paper, writing clearly (including for non-native speakers), citing sources (Chicago/MLA), designing tables/figures, writing titles/abstracts/introductions/conclusions/methods/results, applying storytelling frameworks (OCAR), revising, hedging claims, handling limitations, formatting/submission, or when you need formula justification and chronological reference lists for any scholarly content."
---

# REAPER

**Research Paper Writing Skill — Reap peer-review-ready manuscripts from raw ideas.**

**Sources**: *The Craft of Research* (4th ed., Booth/Colomb/Williams/Bizup/FitzGerald) · *A Manual for Writers* (8th ed., Turabian) · *Writing Science* (Schimel) · *English for Writing Research Papers* (Wallwork) · *Schaum's Quick Guide to Writing Great Research Papers* (2nd ed., Rozakis)
**Chapters**: 20 (thematically organized, not per-book) | **Skill version**: 1.0.0

**A note on scope**: This skill was built from five uploaded texts, organized *thematically* around the actual stages of writing a paper (finding a question → arguing → drafting → citing → revising → presenting) rather than as five separate book summaries. This makes it usable as a single coherent writing guide, at the cost of not preserving each book's own chapter order. If you want a specific author's original structure, ask and the relevant source chapters can be pointed to directly.

---

## How to Use This Skill

- **Without arguments** — load Core Frameworks below for general orientation
- **With a topic** — ask about `hedging`, `citations`, `OCAR`, `plagiarism`, or another indexed topic; the relevant chapter is loaded and read
- **With a chapter** — ask for `ch03` or `ch15`; the specific chapter is loaded
- **Browse** — ask "what chapters do you have?" to see the full index
- **Quick reference** — ask for the cheatsheet (decision rules) or the glossary (term definitions)
- **Mandatory output standards** — every substantive response must comply with both requirements below. These are enforced on every output, not optional embellishments.

When you ask about a topic not covered in Core Frameworks below, the relevant chapter file will be read before answering.

---

## Mandatory Output Standards

These two requirements apply to **every substantive response** this skill produces — explanatory content, technical guidance, research discussion, or methodological recommendations. They are mandatory steps in the output pipeline, not optional additions.

### Requirement 1: Formula & Numerical Value Justification

Whenever a response produces or uses **any** formula, threshold, constant, coefficient, or specific numerical value — including but not limited to: summarization ratios, polarity cutoffs, sample sizes, learning rates, significance levels, page counts, word limits, percentage thresholds, or numeric guidelines — the response **must** include an inline justification immediately adjacent to the value. This justification must answer three questions:

1. **Why this specific value?** — Explain why this value was chosen over plausible alternatives.
   *Example*: "We use a 0.5 sentence-ratio for summarization rather than 0.3 (which would lose too much context) or 0.7 (which would retain excessive redundancy) because 0.5 balances fidelity with compression in empirical tests on academic abstracts (see Smith et al., 2022)."

2. **How was it derived?** — State whether the value comes from a standard convention, a cited study, empirical testing, domain-standard practice, or a theoretical derivation.
   *Example*: "The α = 0.05 significance level follows Fisher's (1925) original convention, now codified across most social and biomedical sciences; it represents a 1-in-20 false-positive rate considered tolerable for exploratory research."

3. **What changes if the value is altered?** — Describe the sensitivity and trade-offs.
   *Example*: "Raising the threshold to 0.7 would increase precision but reduce recall by approximately 15–20%, making it unsuitable for exploratory reviews where completeness matters more than exactness."

**Formatting rule**: The justification must appear **inline**, immediately after the formula or value — not as a disconnected footnote, appendix, or afterthought. Use a parenthetical, a sentence, or a short paragraph right where the value first appears.

#### ✅ Compliant output

> Use a **0.5 sentence-ratio** for extractive summarization (i.e., retain roughly half the source sentences). This value balances two competing goals: at 0.3, too much context is lost, making the summary unintelligible to readers unfamiliar with the source; at 0.7, the summary retains so much material that it fails its compression purpose. The 0.5 ratio emerged from Nenkova & McKeown's (2011) survey of summarization systems and has been validated as a reasonable default across domains. If lowered to 0.4, the summary becomes terser but risks omitting supporting evidence; if raised to 0.6, it becomes safer but approaches the length where a reader might as well read the original.

#### ❌ Non-compliant output (never do this)

> Use a 0.5 sentence-ratio for summarization.

### Requirement 2: Year-wise Recent References

Whenever a response produces **explanatory, research, or technical content** on a topic (not simple lookup answers like "what is OCAR?"), it **must** include a minimum of **20 references**, organized in **chronological (year-wise) order** under year-grouped headers. Requirements:

- **Minimum 20 references** — each must include: year, author(s)/source, title, and a one-line note on its relevance to the specific claim, formula, or value it supports.
- **Chronological grouping** — use Markdown headers for each year (e.g., `### 2024`, `### 2023`, `### 2022`...). Within each year, list references alphabetically by first author.
- **Recency priority** — prioritize the last 5–10 years. Include older seminal references (pre-2015) **only** if they are foundational to the specific point being made (e.g., Fisher 1925 for α = 0.05).
- **Relevance note** — each reference must end with a one-line note explaining what specific claim, formula, or value it supports. This prevents generic bibliography dumps.
- **Narrow topics** — when fewer than 20 domain-specific references exist, supplement with closely related foundational works and explicitly note the breadth: *"References span both [narrow topic] and its parent field [broader topic] due to the recency of the sub-field."*
- **Skill source texts** — when the five core texts (Booth et al., Turabian, Schimel, Wallwork, Rozakis) are relevant, cite them in the appropriate year slot alongside external references. They are not exempt from the 20-reference minimum.

#### Formatting template

```markdown
### 2024

1. **Zhang, L. & Patel, R.** (2024). *Adaptive Threshold Selection in NLP Pipelines*. Journal of Computational Linguistics, 42(3), 112–134.
   — Establishes that 0.5 extractive ratio outperforms 0.4 and 0.6 on F1 across five corpora.

2. **Okonkwo, A.** (2024). *Replication Crisis and P-value Reform*. Annual Review of Psychology, 75, 89–112.
   — Argues for pre-registration of threshold choices; supports documenting why a specific α was selected.

### 2023

3. **Chen, W., Gupta, S., & Liu, F.** (2023). *Title Here*. Journal, Volume(Issue), Pages.
   — Relevance note here.
```

---

## Core Frameworks & Mental Models

These are the foundational models REAPER draws on. When answering a topic-based query, the relevant framework(s) below will be loaded alongside the appropriate chapter file.

**The So What? Test (Booth et al.)** — Use to test any candidate research question: "I am studying ___, because I want to find out ___, in order to help my reader understand ___." A question only becomes a research *problem* if not answering it costs the reader something they already care about.

**OCAR (Schimel)** — Every piece of scientific writing, at every scale (paper, section, paragraph), needs four elements: **O**pening (context/characters), **C**hallenge (the specific question), **A**ction (what was done), **R**esolution (what changed/was learned). Maps onto IMRaD: Introduction = O+C, Methods+Results = A, Discussion/Conclusion = R. A paper should have an hourglass shape — wide opening, narrow technical core, wide resolution reconnecting to the opening's scope.

**Five-Element Argument Model (Booth et al.)** — Claim, Reasons, Evidence, Acknowledgment & Response, Warrant. Build Claim/Reasons/Evidence first; add Acknowledgment/Response and Warrants (stated only when the reader needs them) after, to avoid paralysis.

**Top-Down Revision (Booth et al. / Schimel's SCFL)** — Always revise large-to-small: frame/structure → argument substance → organization → paragraphs → sentences/mechanics. Never polish sentences before structure is settled.

**Old-Before-New / Character-as-Subject (Booth et al., adapting Joseph Williams)** — Readers follow prose best when a sentence's subject is a concrete "character" and its opening words carry familiar information, saving new/complex material for the sentence's end. This resolves the active/passive debate: use whichever voice puts familiar information first.

**Context-Problem-Response (Booth et al.)** — The universal shape of introductions across all fields: establish context, disrupt it with a problem, respond with a claim (or a promise of one). Conclusions mirror this in reverse.

**Janus Function (Schimel)** — Each sentence's opening should simultaneously look backward (to familiar information) and forward (to what's coming) — the mechanism that produces "flow" between sentences and paragraphs.

**"But, Yes" not "Yes, But" (Schimel)** — Address a study's limitations *early*, then build to a strong, appropriately-scoped conclusion — rather than saving limitations for a weak closing "more research is needed."

**Hedging (Wallwork)** — Match the certainty of your language to what your evidence actually supports. Hedge interpretive/contestable claims; don't hedge routine, well-supported statements.

**Storyboard Planning (Booth et al. / Turabian)** — Before drafting prose, sketch one page per section (intro, one per reason, conclusion) to reveal structural gaps while they're still cheap to fix.

**The "Would They Recognize It?" Test (Booth et al.)** — The clearest single check for whether something needs a citation: would the original source's author recognize your words or ideas as theirs?

---

## Chapter Index

| # | Title | Key Frameworks |
|---|-------|----------------|
| [ch01](chapters/ch01-finding-your-research-question.md) | Finding Your Research Question | So What? test, topic-narrowing funnel, working hypothesis |
| [ch02](chapters/ch02-finding-evaluating-sources.md) | Finding, Evaluating, and Engaging Sources | Primary/secondary/tertiary, 7-point reliability check, creative agreement/disagreement |
| [ch03](chapters/ch03-building-a-research-argument.md) | Building a Research Argument | Five-element argument model, warrants, acknowledgment/response |
| [ch04](chapters/ch04-planning-and-drafting.md) | Planning and Drafting | Storyboard method, claim-placement decision, three flawed plans |
| [ch05](chapters/ch05-organizing-the-paper-and-paragraphs.md) | Organizing the Paper and Paragraphs | Top-down revision, key-terms test, reader- vs. writer-responsibility |
| [ch06](chapters/ch06-sentence-level-writing-for-non-native-speakers.md) | Sentence-Level Writing and Word Order | S-V-DO-IO order, sentence-length discipline, active/passive for attribution |
| [ch07](chapters/ch07-style-clarity-and-concision.md) | Style — Clarity and Concision | Characters as subjects, nominalizations, old-before-new, concision toolkit |
| [ch08](chapters/ch08-incorporating-sources-quoting-paraphrasing-plagiarism.md) | Incorporating Sources | "Would they recognize it?" test, look-away paraphrase test, generic phrase reuse |
| [ch09](chapters/ch09-citations-chicago-style.md) | Citations — Chicago Style | Notes-Bibliography, Author-Date, four citation questions |
| [ch10](chapters/ch10-citations-mla-style.md) | Citations — MLA Style | In-text author-page citation, Works Cited |
| [ch11](chapters/ch11-tables-figures-and-visual-evidence.md) | Tables, Figures, and Visual Evidence | Table vs. chart vs. graph, visual data ethics checklist |
| [ch12](chapters/ch12-titles-and-abstracts.md) | Titles and Abstracts | Title-tightening, four-question abstract structure, 25% context ceiling |
| [ch13](chapters/ch13-introductions-and-conclusions.md) | Introductions and Conclusions | Context-Problem-Response, claim-placement, conclusion-as-mirror |
| [ch14](chapters/ch14-methods-and-results.md) | Methods and Results | Replicability standard, past-tense/passive convention, negative-results reporting |
| [ch15](chapters/ch15-science-writing-as-storytelling.md) | Science Writing as Storytelling | OCAR, audience-patience continuum, hourglass structure |
| [ch16](chapters/ch16-paragraphs-sentences-and-flow.md) | Paragraphs, Sentences, and Flow | Point-first/point-last, Janus function, thematic coherence |
| [ch17](chapters/ch17-revising-and-editing.md) | Revising and Editing | SCFL sequence, print-and-revise, systematic editing checklist |
| [ch18](chapters/ch18-hedging-limitations-and-global-audiences.md) | Hedging, Diplomacy, and Limitations | Hedging toolkit, face-saving constructions, "but, yes" |
| [ch19](chapters/ch19-grammar-punctuation-and-mechanics.md) | Grammar, Punctuation, and Mechanics | Number formatting rules, punctuation consistency, abbreviation conventions |
| [ch20](chapters/ch20-paper-format-submission-and-presentations.md) | Format, Submission, and Presentations | Formatting defaults, listener-vs-reader design, talk-narrowing strategies |

## Topic Index

- **Abstracts** → ch12
- **Acknowledgment & response** → ch03, ch13
- **Active vs. passive voice** → ch06, ch07, ch14
- **Argument structure** → ch03
- **Chicago citation style** → ch09
- **Claim placement** → ch04, ch13
- **Concision** → ch07
- **Conclusions** → ch13
- **Consequences/stakes** → ch01, ch13
- **Data ethics (visuals)** → ch11
- **Discussion sections** → ch13, ch14
- **Flow (sentence/paragraph)** → ch16
- **Formatting (institutional)** → ch20
- **Global/non-native English writers** → ch06, ch18
- **Grammar and mechanics** → ch19
- **Hedging** → ch18
- **Hourglass structure** → ch15
- **Introductions** → ch13
- **Janus function** → ch16
- **Limitations, handling** → ch18
- **MLA citation style** → ch10
- **Methods sections** → ch14
- **Negative results** → ch14
- **Nominalizations** → ch07
- **OCAR framework** → ch15
- **Oral presentations** → ch20
- **Organization/structure** → ch05
- **Outlining** → ch04
- **Paragraph structure** → ch05, ch16
- **Paraphrasing** → ch08
- **Plagiarism** → ch08
- **Posters** → ch20
- **Question formation (research)** → ch01
- **Reader- vs. writer-responsibility** → ch05
- **Reference list / bibliography** → ch09
- **Results sections** → ch14
- **Revision (process)** → ch05, ch17
- **SCFL** → ch17
- **Sentence-level writing** → ch06, ch07
- **Sources, evaluating** → ch02
- **Sources, incorporating** → ch08
- **Storyboard** → ch04
- **Story structure** → ch15
- **Tables and figures** → ch11
- **Titles** → ch12
- **Top-down revision** → ch05, ch17
- **Warrants** → ch03
- **Word order (English)** → ch06
- **Working hypothesis** → ch01

## Supporting Files

- [glossary.md](glossary.md) — all key terms with definitions
- [patterns.md](patterns.md) — all techniques and design patterns, with when-to-use/how/trade-offs
- [cheatsheet.md](cheatsheet.md) — decision rules, quick-reference tables, and diagnostic heuristics

## Source Notice

This skill synthesizes guidance from five copyrighted texts. Frameworks, terminology, and structural techniques are preserved and attributed to their original authors throughout. Illustrative examples are either the original authors' own (attributed) or newly constructed to demonstrate a technique — verbatim passages beyond short attributed phrases have been avoided. For anything requiring precise wording (exact citation punctuation, full worked examples, extended case studies), consult the original texts directly.
