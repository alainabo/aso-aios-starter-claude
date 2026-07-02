# ASO AIOS Starter (Claude Edition)

**By [ASO Ltd.](https://www.asoltd.info) — the digital backbone of African business.**

A free, MIT-licensed starter kit that turns **Claude Code** into your personal **AI Operating System (AIOS)**. Claude-native from the ground up: `CLAUDE.md` as the operating manual, auto-discovered skills in `.claude/skills/`, hooks and MCP for the automation layer.

The kit personalizes itself to you via a `/onboard` interview, then gives you two recurring thinking skills (`/audit`, `/level-up`) to keep building leverage week over week.

This is the same architecture ASO Ltd. runs its own operations on — daily content automation, research loops, decision logging, dual-agent code review. We ship it free because a business that runs on an AIOS is a business that's ready for everything else we build.

> Using OpenAI Codex instead? Grab the sibling kit: **[ASO AIOS Starter (Codex Edition)](https://github.com/alainabo/codex-aios-template)** — same architecture, Codex-native conventions.

---

## The litmus test

> **"While you're not at your desk, your AIOS observes one real-world event and produces an output that's faster and more accurate than what you'd produce yourself."**

Every design decision in this kit rolls up to that test.

---

## Two frameworks (unchanged from the original kit)

The kit teaches two complementary frameworks. **Three Ms first, Four Cs second.** Without the brain rewire, the architecture is just a folder structure.

### The Three Ms — operator brain (how you think)

| M | One-liner |
|---|---|
| **Mindset** | Default Shift, Function Breakdown, Curiosity Rule. *To what extent can AI be leveraged here?* |
| **Method** | Find Constraint → EAD (Eliminate, Automate, Delegate) → Map Process → Pick Autonomy Level → Tie to KPI. |
| **Machine** | Lego Principle, Validation Chain, Bike Method, Intern Rule, Kill Switch. *Boring is beautiful. Workflows beat agents.* |

Full breakdown in `references/3ms-framework.md`. The `/level-up` skill walks you through all three weekly.

> *The Three Ms of AI™ is a trademark of Nate Herk. © 2026 Nate Herk.*

### The Four Cs — architecture (what you build)

| # | Layer | One-liner | "This layer is in place" test |
|---|---|---|---|
| 1 | **Context** | Knows your business | Fresh Claude session answers "what does this business do and who works here?" without browsing |
| 2 | **Connections** | Reaches your stuff | "What's on my calendar tomorrow and what tasks are due?" → live data, no paste |
| 3 | **Capabilities** | Knows how to do the work | A short phrase triggers a multi-step workflow that produces an artifact |
| 4 | **Cadence** | Runs without being asked | Laptop closed. A brief lands in the inbox. A teammate messages it and gets a real answer |

**Brand line:** Context. Connections. Capabilities. Cadence.

> *The Four Cs of an AIOS™ is a trademark of Nate Herk. © 2026 Nate Herk.*

Dependency graph: Context is non-skippable. Connections + Capabilities can build in parallel. Cadence is last — don't automate workflows that don't work manually.

---

## What ships — 3 skills

| Skill | Type | When to run |
|---|---|---|
| `/onboard` | Setup wizard (one-time) | Day 1, right after clone. 7-question interview. Generates Day-1 file set + fills `CLAUDE.md`. |
| `/audit` | Recurring thinking skill | Day 7, then weekly. Four-Cs gap report. Read-only. |
| `/level-up` | Recurring thinking skill | Day 14, then weekly. Three Ms interview. One run = one shipped artifact. |

Skills are auto-discovered from `.claude/skills/` — no registration, no hidden machinery. Open any `SKILL.md` and read exactly what it does.

---

## Quick start

1. **Clone this repo** to a working folder on your machine.
2. **Open it in Claude Code** and run `/onboard`. Answer the 7 questions honestly — voice samples must be pasted, not described. ~15 minutes.
3. **Use it for a week.** Bring real questions, make real decisions, log them to `decisions/log.md`.
4. **Day 7:** run `/audit`. Read the gap report, fix one gap.
5. **Day 14:** run `/level-up`. One automation gets scoped and shipped.
6. **Week 3+:** weekly `/level-up` ritual.

---

## Repo layout

```
aso-aios-starter-claude/
├── README.md
├── CLAUDE.md                        ← Your operating manual (filled by /onboard)
├── EXPANSIONS.md                    ← What to add as you grow
├── LICENSE
├── .gitignore
├── aios-intake.md                   ← Source-of-truth for /onboard. Edit + re-run any time.
├── connections.md                   ← Registry of every system your AIOS can reach
├── context/                         ← About you, your business (filled by /onboard)
├── references/
│   └── 3ms-framework.md             ← The operator brain
├── decisions/
│   └── log.md                       ← Append-only record of what was decided and why
├── archives/                        ← Old stuff. Don't delete. Move here.
└── .claude/
    └── skills/
        ├── onboard/SKILL.md
        ├── audit/SKILL.md
        └── level-up/SKILL.md
```

See `EXPANSIONS.md` for what to add as you grow.

---

## Want this running inside your business?

Cloning the kit takes a minute. Wiring it into your actual business — payments data, WhatsApp, calendars, dashboards, automations that run while you sleep — is what **ASO Ltd.** does for clients across Cameroon and Central Africa.

**AI & Intelligent Automation** is one of our eight service lines: custom AI models, document intelligence, workflow automation, and AI-powered applications — built for XAF, MTN/Orange Mobile Money, French and English.

- **Talk to us:** [consult@asoltd.info](mailto:consult@asoltd.info) — we respond within 24 hours
- **See what we build:** [www.asoltd.info](https://www.asoltd.info)

---

## License + attribution

MIT License. © 2026 Nate Herk (original AIS-OS starter kit); © 2026 ASO Ltd. (this edition and modifications). Distributed under the same MIT terms.

The Three Ms of AI™ and The Four Cs of an AIOS™ are trademarks of Nate Herk. Both frameworks ship in this repo with attribution. Use freely; don't repackage as your own.
