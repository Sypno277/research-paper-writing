<p align="center"><img src="logo.jpg" width="200" alt="REAPER Logo"/></p>

# REAPER

**Research Paper Writing Skill — Reap peer-review-ready manuscripts from raw ideas.**

REAPER is a knowledge-base skill synthesizing five authoritative research-writing textbooks into a single, thematically organized writing guide. It covers every stage of the research-paper lifecycle — from finding a question through arguing, drafting, citing, revising, and presenting — with mandatory rigor standards built in.

---

## What It Does

REAPER provides structured guidance drawn from:

| Source | Author(s) | Edition |
|--------|-----------|---------|
| *The Craft of Research* | Booth, Colomb, Williams, Bizup & FitzGerald | 4th |
| *A Manual for Writers of Research Papers, Theses, and Dissertations* | Turabian | 8th |
| *Writing Science* | Schimel | 1st |
| *English for Writing Research Papers* | Wallwork | 2nd |
| *Schaum's Quick Guide to Writing Great Research Papers* | Rozakis | 2nd |

### Coverage

- 🔍 **Finding a research question** — topic narrowing, So What? test, working hypotheses
- 🏗️ **Building arguments** — five-element model, warrants, acknowledgment & response
- ✍️ **Drafting & organizing** — storyboard planning, top-down revision, paragraph structure
- 📖 **Incorporating & citing sources** — paraphrasing, plagiarism detection, Chicago & MLA styles
- 📊 **Visual evidence** — tables, figures, charts, data ethics
- 🎯 **Titles, abstracts, introductions, conclusions** — structure and revision techniques
- 🔬 **Methods & results** — replicability, tense/voice conventions, negative results
- 📖 **Storytelling in science** — OCAR framework, hourglass structure
- 🔧 **Revising & editing** — SCFL sequence, systematic checklists
- ⚖️ **Hedging & limitations** — diplomatic language, "but, yes" sequencing
- 📝 **Grammar & formatting** — mechanics, submission, and presentations

### Mandatory Output Standards

Every substantive response from REAPER enforces two non-optional requirements:

1. **Formula & Numerical Value Justification** — Any formula, threshold, constant, or numerical value must include an inline explanation of *why* that value was chosen, *how* it was derived, and *what changes* if it were altered.

2. **Year-wise Recent References** — Any explanatory or technical content must include ≥20 references organized chronologically by year, each with a one-line relevance note.

These are not embellishments — they are enforced steps in the output pipeline.

---

## Installation

### For Claude Desktop / Claude Code

1. Clone this repository into your Claude skills directory:

```bash
git clone https://github.com/<your-username>/reaper.git ~/.claude/skills/reaper
```

2. The skill auto-activates when you ask about research-paper writing topics. No configuration needed.

### For Claude Projects (claude.ai)

1. Upload the entire `reaper` folder as project knowledge.
2. Claude will reference SKILL.md and all chapter/supporting files when answering research-writing questions.

---

## Usage

| Command | What Happens |
|---------|-------------|
| *No argument* | Loads Core Frameworks for general orientation |
| `hedging`, `citations`, `OCAR`... | Loads and reads the relevant chapter |
| `ch03`, `ch15`... | Loads a specific chapter |
| "what chapters do you have?" | Shows the full chapter index |
| `cheatsheet` / `glossary` | Quick reference lookup |

---

## Project Structure

```
reaper/
├── SKILL.md              # Main skill definition (Claude skill entry point)
├── README.md             # This file
├── LICENSE               # MIT License
├── .gitignore            # Git ignore rules
├── logo.jpg              # REAPER logo
├── cheatsheet.md         # Decision rules & quick-reference tables
├── glossary.md           # All key terms with definitions
├── patterns.md           # Techniques & design patterns with trade-offs
└── chapters/             # 20 thematically organized chapters
    ├── ch01-finding-your-research-question.md
    ├── ch02-finding-evaluating-sources.md
    ├── ch03-building-a-research-argument.md
    ├── ch04-planning-and-drafting.md
    ├── ch05-organizing-the-paper-and-paragraphs.md
    ├── ch06-sentence-level-writing-for-non-native-speakers.md
    ├── ch07-style-clarity-and-concision.md
    ├── ch08-incorporating-sources-quoting-paraphrasing-plagiarism.md
    ├── ch09-citations-chicago-style.md
    ├── ch10-citations-mla-style.md
    ├── ch11-tables-figures-and-visual-evidence.md
    ├── ch12-titles-and-abstracts.md
    ├── ch13-introductions-and-conclusions.md
    ├── ch14-methods-and-results.md
    ├── ch15-science-writing-as-storytelling.md
    ├── ch16-paragraphs-sentences-and-flow.md
    ├── ch17-revising-and-editing.md
    ├── ch18-hedging-limitations-and-global-audiences.md
    ├── ch19-grammar-punctuation-and-mechanics.md
    └── ch20-paper-format-submission-and-presentations.md
```

---

## Core Frameworks

REAPER draws on these mental models throughout:

- **So What? Test** — Validates that a research question has real stakes
- **OCAR** — Opening, Challenge, Action, Resolution — the universal story structure of scientific writing
- **Five-Element Argument Model** — Claim → Reasons → Evidence → Acknowledgment/Response → Warrant
- **Top-Down Revision / SCFL** — Revise structure first, sentences last
- **Old-Before-New** — Familiar information first, new information last
- **Context-Problem-Response** — The universal introduction structure
- **Janus Function** — Each sentence looks backward and forward simultaneously
- **"But, Yes"** — Limitations early, strong conclusion last
- **Hedging** — Match certainty to evidence strength
- **Storyboard Planning** — Sketch sections before drafting prose
- **"Would They Recognize It?"** — The citation litmus test

---

## Source Notice

This skill synthesizes guidance from five copyrighted texts. Frameworks, terminology, and structural techniques are preserved and attributed to their original authors. Illustrative examples are either the original authors' own (attributed) or newly constructed to demonstrate a technique. For precise wording, consult the original texts directly.
