# Keri Janschitz — AI Content Designer Portfolio

> Live: **[https://kerij12.github.io/keri-portfolio/](https://kerij12.github.io/keri-portfolio/)**

This repository is the source for my AI Content Designer portfolio, built in May 2026 specifically in response to LOOP Digital Agency's brief: an AI Content Designer who builds **scalable workflows (1→100 variations)** for FMCG and global brands.

## What's in here

Four case studies — deliberately different shapes, each answering a different question a hiring manager might ask:

| Shape | Case | Question it answers |
|---|---|---|
| **Hero · Real client deployment** | [MR.ZHU Chinese Streetfood](https://kerij12.github.io/keri-portfolio/cases/mrzhu/) | *Does her system deliver measurable outcome on a paying client?* — Yes: +550% monthly Reel views, Klagenfurt restaurant, 3 months. |
| **Co-Hero · Spec project** | [Audi Vorsprung Local](https://kerij12.github.io/keri-portfolio/cases/audi/) | *Does her thinking scale to LOOP-tier client?* — Yes: full spec system for one Audi e-tron creative idea → 60-cell variant matrix across 6 European markets, end-to-end designed. |
| **Practice · Daily public log** | [AIGrowth Lab](https://kerij12.github.io/keri-portfolio/cases/agl/) | *Is "lead by doing" a habit or a slogan?* — Habit: 34 documented operational experiments since 22 March 2026, near-daily cadence. |
| **Track Record · Pre-AI foundation** | [Munich Fabric Start Playbook](https://kerij12.github.io/keri-portfolio/cases/munich/) | *Is her systems thinking the substrate, or did AI create it?* — Substrate: 4-month → 1.5-month prep-time compression across 8 trade-fair editions, mostly pre-AI. |

## How the site is built

Static HTML + CSS, deployed via GitHub Pages. No build step, no framework. Markdown-rendered case content via [marked.js](https://marked.js.org/). Editorial typography (Fraunces serif + Inter + JetBrains Mono) on a restrained palette. Designed for fast first-paint and clean print rendering.

The visual restraint follows three reference DNAs that the Audi case study documents in detail:
- **Hammershøi** — light discipline
- **Saul Leiter** — color discipline
- **Wim Wenders** — framing discipline

## Repository structure

```
.
├── index.html              ← landing page (hero + 4 case teasers + about)
├── styles/main.css         ← single shared stylesheet
├── cases/
│   ├── mrzhu/index.html    ← Hero case
│   ├── audi/index.html     ← Co-Hero case (5 sub-docs concatenated)
│   ├── agl/index.html      ← Practice case
│   └── munich/index.html   ← Track-record case
├── assets/
│   ├── mrzhu/              ← 6 deployment artifacts
│   ├── audi/               ← 6 hero cell renders (Lifestyle audience × Reel format)
│   └── munich/             ← 5 trade-fair artifacts
├── .nojekyll               ← prevent Jekyll processing on GitHub Pages
└── README.md               ← this file
```

## Tooling stack (transparent)

The portfolio's premise is that AI is a system, not a tool. Showing the actual stack used to build it is part of that premise.

- **Claude Code** — agentic orchestration, content drafting, system-architecture documentation
- **Gemini Imagen** — Audi hero cell image generation (with reference imagery anchor library and full negative-prompt block)
- **My existing Claude Skill files** — the AGL design systems (M-series, C-series, I-series, Quiz Reel, Cover Tester) ported into MR.ZHU deployment
- **Hand-edited HTML/CSS** — final composition and layout
- **GitHub Pages** — hosting

## Contact

Keri (Shu Jung) Janschitz
Nötsch im Gailtal, Carinthia, Austria
[kerijanschitz@outlook.com](mailto:kerijanschitz@outlook.com)

Currently applying to LOOP Digital Agency — AI Content Designer, Salzburg.
