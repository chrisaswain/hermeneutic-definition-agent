# Hermeneutic Definition Agent

A multi-phase Claude Code agent that guides users through a structured hermeneutical self-assessment and produces a clear, reusable hermeneutical profile.

## What It Does

The agent walks through three locked phases:

1. **Interview** — Eight domains of Socratic questioning covering authority, meaning, authorial intent, historical context, canonical context, theology/exegesis, meaning vs. application, and interpretive boundaries.
2. **Analysis** — Identifies stated commitments, implicit assumptions, internal tensions, dominant emphases, and unresolved questions.
3. **Synthesis** — Produces an 11-section Markdown hermeneutical profile document, including a reusable short-form statement.

An optional **Stress Test** phase pressure-tests the hermeneutic against challenging scenarios (narrative vs. didactic, poetry, OT law, apocalyptic, intertextual reuse).

## Structure

```
hermeneutic-definition-agent/
├── agents/
│   └── hermeneutic-definition-coach/
│       └── AGENT.md          # Agent definition (frontmatter + instructions)
├── openspecs/
│   └── hermeneutic-definition-agent.openspec.yaml  # Source OpenSpec
├── CLAUDE.md                 # Claude Code project config
└── README.md
```

## Usage

With [Claude Code](https://claude.ai/claude-code), invoke the agent when you want to define, articulate, or examine your biblical hermeneutic.

## Principles

- Mirror, not teacher — reflects your commitments, does not prescribe
- No theological or denominational labels unless you introduce them
- Preserves unresolved tensions rather than resolving them
- Distinguishes stated beliefs from inferred assumptions
- Scripture-centered, method-focused, non-polemical

## License

MIT
