# Local SEO — Master Practitioner SME

> Subject-matter expert on SEO for local businesses (Google Business Profile, local pack, local organic, citations, reviews, schema, service-area businesses). US/Canada primary. Built from 49 videos of practitioner content.

**Free. Apache 2.0. Bring-your-own-Claude.**

## What this is

A Claude skill bundle — a sanitized, attributed, downloadable subject-matter expert that runs inside Claude Code, Claude Desktop, or any Claude-API workflow. Drop it in, invoke it, get answers grounded in real practitioner content rather than generic LLM consensus.

Use this SME for any question about helping a local business get found in Google search, Maps, the local pack, AI Overviews, or Ask Maps.

## Install

```bash
# Claude Code plugin install (one-line)
claude plugin install sme-local-seo --from https://fadaly.net/downloads/skills/sme-local-seo.zip
```

Or clone this repo into your Claude skills directory:

```bash
git clone https://github.com/MomoFadaly/sme-local-seo.git ~/.claude/skills/sme-local-seo
```

Or download the zip from [fadaly.net/skills/sme-local-seo](https://fadaly.net/skills/sme-local-seo) and extract into `~/.claude/skills/`.

## What's in the bundle

| File | Size |
|---|---|
| `anti-patterns.md` | 14KB |
| `canon.md` | 37KB |
| `CHANGELOG.md` | 4KB |
| `concepts.json` | 11KB |
| `mental-models.md` | 10KB |
| `SKILL.md` | 18KB |
| `sources.md` | 7KB |
| `thumb.png` | 700KB |
| `verification-results.json` | 7KB |
| `verification-targets.json` | 20KB |

Total: 827KB

## Sources

This SME's canon was built from these practitioners. Every claim in the canon is attributed.

- Whitespark 2026 Local Search Ranking Factors (Darren Shaw)
- Sterling Sky's live audit content (Joy Hawkins, Liz, Carrie Hill, Colan Nielsen)
- SearchLab (Greg Gifford)
- Near Media (Mike Blumenthal)

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
