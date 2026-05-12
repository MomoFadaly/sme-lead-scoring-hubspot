# HubSpot Lead Scoring SME

> Practitioner-voice expert on HubSpot Lead Scoring at the post-Aug-31-2025 sunset moment. Covers the new Lead Scoring tool (Marketing Hub Pro/Enterprise + Sales Hub Pro/Enterprise), fit and engagement scoring, AI scoring, combined-score threshold property, MQL/SQL handoff, decay vs Time Frame, and the legacy-to-new migration.

**Free. Apache 2.0. Bring-your-own-Claude.**

## What this is

A Claude skill bundle — a sanitized, attributed, downloadable subject-matter expert that runs inside Claude Code, Claude Desktop, or any Claude-API workflow. Drop it in, invoke it, get answers grounded in real practitioner content rather than generic LLM consensus.

Use when the question mentions HubSpot Lead Scoring, the Aug 31 2025 retirement of hubspotscore, fit/engagement decomposition, AI/predictive scoring, MQL threshold calibration, decay configuration, or score-history debugging.

## Install

```bash
# Claude Code plugin install (one-line)
claude plugin install sme-lead-scoring-hubspot --from https://fadaly.net/downloads/skills/sme-lead-scoring-hubspot.zip
```

Or clone this repo into your Claude skills directory:

```bash
git clone https://github.com/MomoFadaly/sme-lead-scoring-hubspot.git ~/.claude/skills/sme-lead-scoring-hubspot
```

Or download the zip from [fadaly.net/skills/sme-lead-scoring-hubspot](https://fadaly.net/skills/sme-lead-scoring-hubspot) and extract into `~/.claude/skills/`.

## What's in the bundle

| File | Size |
|---|---|
| `canon.md` | 70KB |
| `concepts.json` | 24KB |
| `SKILL.md` | 20KB |
| `thumb.png` | 1.11MB |
| `verification-results.json` | 55KB |
| `verification-targets.json` | 19KB |

Total: 1.29MB

## Sources

This SME's canon was built from these practitioners. Every claim in the canon is attributed.

- HubSpot Knowledge Base (primary)
- Aptitude 8 (Authority Brands rebuild case)
- RevPartners · Xcellimark · Kiwi Creative · Six-and-Flow
- On The Fuze · Neighbourhood Co. · StruckAg
- Bryce Finnerty (Dealflow Dynamics) · Doug Digital · Lex Hultquist
- HubSpot Admin HUG (Melody)

Primary sources (official documentation, peer-reviewed research) take priority over practitioner consensus, which takes priority over single-source claims. Confidence tiers are tagged inline.

## How it works

Claude reads `SKILL.md` as the system instructions for the skill. Supporting files (`canon.md`, `mental-models.md`, etc.) are loaded as reference material when the skill needs to answer off the cuff or cite a specific source.

When you ask a question this SME covers, Claude pulls the relevant canon entry, names its source, tags its confidence level, and pushes back if your question contradicts canon.

## Confidence levels

- **Verified** — primary source + practitioner corroboration. Treat as fact.
- **Confirmed** — practitioner consensus across credible voices, no primary contradiction. Defended best-practice.
- **Plausible** — single-source or thin evidence. Working hypothesis until validated.
- **Disputed** — credible voices disagree. The SME names the camps and gives you the lens to decide.
- **Stale** — once true, contradicted by current docs/data. Flagged for refresh.

## License

Apache License 2.0. See [LICENSE](LICENSE).

You are free to use, modify, redistribute, and build on this skill. Attribution to the original practitioners (named in `sources.md` or `SKILL.md`) is morally required even if not legally; their work made the canon possible.

## Built by

[Mo Fadaly](https://fadaly.net) — AI intrapreneur, runs Claude skills in production.

This is one of a series. See the [full skill catalog at fadaly.net/skills](https://fadaly.net/skills).
