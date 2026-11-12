# Agent Skills Radar

A weekly, evidence-based ranking of trending agent skills (SKILL.md packages for Claude Code, GitHub Copilot, Codex, Cursor, Gemini CLI and similar agents). It tracks GitHub, skill registries, Hacker News and YouTube, and flags any publicly reported security concerns.

**Website:** https://kumar-ashwin-hubert.github.io/agent-skills-radar/ · **RSS:** [feed.xml](feed.xml)

## Latest report: week ending 12 November 2026

**[Read the full report →](reports/2026-11-12.md)**

### Top 5 this week

| # | Skill | Section | Why it's trending |
|---|---|---|---|
| 1 | [Modern Web Guidance](https://github.com/GoogleChrome/modern-web-guidance) | Frontend & Design | v1.0 on 10 Nov; +38.3% stars in 7 days; HN front page; 3.1K trending installs on skills.sh |
| 2 | [rea-video](https://github.com/JuneYaooo/rea-video) | Media & Video | +640% stars in 7 days, the fastest riser on HotSkills |
| 3 | [Elephant-Goldfish-Model](https://github.com/google/elephant-goldfish-model) | Coding & Engineering | +47.2% stars in 7 days; Google Open Source blog launch |
| 4 | [mattpocock/skills](https://github.com/mattpocock/skills) | Coding & Engineering | Most-starred skill repo (321.4k, +2.6%); featured in YouTube roundups |
| 5 | [HyperFrames](https://github.com/heygen-com/hyperframes) | Media & Video | 17.6K trending installs on skills.sh; +4.5% stars |

### Headline trends

- **Google is this week's biggest mover:** Modern Web Guidance 1.0 and Elephant-Goldfish-Model.
- **Video and motion skills dominate fast growth:** rea-video, bang-motion, scenario-labs, pixelfx and HyperFrames.
- **The big libraries keep compounding:** mattpocock/skills, obra/superpowers and anthropics/skills.
- **Design-quality skills are a steady theme:** impeccable, taste-skill and ui-ux-pro-max.
- **Supply-chain risk remains live:** look-alike "superpowers" publishers on skills.sh. Install from vendor-owned sources only.

## How skills are ranked

Each skill gets a momentum score built from evidence only:

- 7-day growth rate: 30%
- Absolute weekly gain in stars or installs: 30%
- Number of platforms where it was seen: 25%
- Overall popularity: 15%

Skills are assigned to one of 12 fixed sections:

- Coding & Engineering
- Frontend & Design
- Testing & QA
- DevOps & Cloud
- Data & Analytics
- Docs & Writing
- Office & Productivity
- Security
- Media & Video
- Research
- Agent-Building & Meta-Skills
- Business & Marketing

A short "Watch out" section lists any skill with a publicly reported security, prompt-injection or licensing concern.

## Data

Each week's figures are saved as JSON in [`data/`](data/) (one file per week: rank, section, stars, 7-day growth, trending installs and signals per skill). Reddit and Hacker News mentions are collected separately into [`signals/`](signals/) each Saturday before the report runs.

## Archive

| Week ending | Report |
|---|---|
| 12 November 2026 | [reports/2026-11-12.md](reports/2026-11-12.md) |

---

*Figures are snapshots from public sources and change daily. Inclusion is not an endorsement. Review any skill's code and permissions before installing it.*
