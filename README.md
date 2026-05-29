# Claude Code SEO Skills — free `seo-meta-generator` skill

> A free, production-grade **SEO skill for Claude Code & Cursor**. Drop it into your AI editor and generate Google-perfect title tags + meta descriptions in one pass. This is one of 11 skills from the [SkillsForge SEO/GEO Pack](https://skillsforge.pitchinsixty.com).

[![Get the full pack](https://img.shields.io/badge/SkillsForge-11%20SEO%2FGEO%20skills-6d28d9)](https://skillsforge.pitchinsixty.com)

## What is a "skill"?

A **skill** is a structured Markdown workflow that drops into `~/.claude/skills/` (Claude Code) or your Cursor rules. Instead of ad-hoc prompting, you get a repeatable, tested procedure your AI editor follows every time — like a senior SEO sitting in your terminal.

## The free skill in this repo: `seo-meta-generator`

For any URL, keyword, or content snippet it produces:

- **Title tag** (50–60 chars, primary keyword, brand suffix)
- **Meta description** (140–160 chars, value + soft CTA)
- **3 A/B variants** per output, with character counts and a pick recommendation

Templates by intent (informational / commercial / transactional), proven CTR levers, anti-patterns, and a GSC tracking checklist. Read it: [`seo-meta-generator/SKILL.md`](./seo-meta-generator/SKILL.md).

## Install (Claude Code)

```bash
git clone https://github.com/kwouz/claude-code-seo-skills.git
mkdir -p ~/.claude/skills
cp -r claude-code-seo-skills/seo-meta-generator ~/.claude/skills/
# restart Claude Code so it picks up the new skill
```

Then just ask: *"write the title tag and meta for this page"* — Claude Code will follow the skill.

**Cursor:** copy `seo-meta-generator/SKILL.md` into your project's `/.cursor/rules/` (or paste as a rule).

## Why structured SEO skills now

AI Overviews now appear on roughly **48% of Google queries** (BrightEdge, 2026). Classic SEO is shifting toward **GEO/AEO** — getting cited *inside* AI answers. Everyone's prompting ChatGPT/Claude for SEO ad-hoc; almost nobody has a repeatable pipeline. That's the gap these skills fill.

## The full pipeline (SkillsForge Pack — 11 skills)

```
keyword-cluster-mapper  →  content-brief-builder  →  seo-pseo-generator
        →  geo-aeo-optimizer  →  schema-markup-engineer
        →  internal-linking-architect  →  technical-seo-auditor
        →  backlink-outreach-engine  →  ai-mentions-monitor
```

| Skill | Use it when |
|---|---|
| `seo-meta-generator` ⭐ free (this repo) | Title + meta in one pass |
| `keyword-cluster-mapper` | Flat keyword list → pillars + clusters + long-tail |
| `content-brief-builder` | Production brief in one pass — H-tree, entities, schema, links |
| `seo-pseo-generator` | Programmatic SEO — 1k–100k pages that rank |
| `geo-aeo-optimizer` | Get cited by ChatGPT, Claude, Perplexity, Gemini, AI Overviews |
| `schema-markup-engineer` | Validated JSON-LD for every page type |
| `internal-linking-architect` | Pillar/cluster topology, orphan rescue, PageRank flow |
| `technical-seo-auditor` | 9-bucket site audit — crawl, render, CWV, hreflang |
| `backlink-outreach-engine` | White-hat outreach + personalized pitches at scale |
| `ai-mentions-monitor` | Daily AI-search share-of-voice dashboard |
| `gbp-local-seo` | Google Business Profile + local citations + reviews |

**Get all 11 → [skillsforge.pitchinsixty.com](https://skillsforge.pitchinsixty.com)** · $49 lifetime (early-bird $39) · $14/mo Pro (monthly new skills + Discord) · $199/yr Team (5 seats)

Or grab the email-gated free skill page: **[skillsforge.pitchinsixty.com/free-skill](https://skillsforge.pitchinsixty.com/free-skill)**

## License

The free `seo-meta-generator` skill is free to use, share, and remix — attribution appreciated. The paid pack skills carry a single-user commercial license.

---

*Built by a working SEO practitioner for real client work. Shipping in public — feedback and PRs welcome.*
