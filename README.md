# SEO Rank

A Claude Code skill for comprehensive SEO auditing and optimization to 2026 standards. Covers content quality, technical performance, site architecture, crawlability, and off-page signals.

Two frameworks, full coverage:
- **SEARCH Framework** (Content SEO) — Intent, E-E-A-T, quality, keywords, CTR, structure
- **TECH Framework** (Technical SEO) — Core Web Vitals, crawling, rendering, security, architecture, i18n, accessibility, structured data, local SEO

## What It Does

- Audits pages and sites against weighted scoring matrices
- Checks Core Web Vitals (LCP, INP, CLS) via Lighthouse CLI
- Validates robots.txt, sitemap.xml, canonical URLs, hreflang tags
- Audits security headers (HSTS, CSP, X-Frame-Options)
- Analyzes content for E-E-A-T signals, keyword coverage, and search intent
- Reviews structured data (JSON-LD schema) and generates missing markup
- Produces prioritized recommendations (quick wins, medium effort, strategic)
- Covers international SEO, accessibility overlap, and local SEO

## Companion Skill

Pairs with [ai-rank](https://github.com/entpnomad/ai-rank) for complete search visibility:
- **seo-rank** handles Google/Bing traditional + technical SEO
- **ai-rank** handles LLM answer engines + autonomous AI agents

Use both together for full coverage across traditional and AI-powered search.

## Installation

```bash
git clone https://github.com/entpnomad/seo-rank.git ~/.claude/skills/seo-rank
```

Or for a specific project:

```bash
git clone https://github.com/entpnomad/seo-rank.git .claude/skills/seo-rank
```

## Usage

```
/seo-rank              # Full workflow (audit + recommendations + implementation)
/seo-rank audit        # Full audit only (SEARCH + TECH scores)
/seo-rank tech         # Technical audit only (CWV, security, crawlability)
/seo-rank content      # Content audit only (intent, E-E-A-T, keywords)
/seo-rank cwv          # Core Web Vitals check only
/seo-rank headers      # Security headers check only
/seo-rank schema       # Structured data audit + generate missing JSON-LD
/seo-rank meta         # Title tag, meta description, OG tags audit
/seo-rank i18n         # International SEO audit (hreflang, localization)
/seo-rank local        # Local SEO audit (GBP, NAP, local schema)
/seo-rank checklist    # Full page + site checklists
/seo-rank site         # Site-level audit (architecture, sitemap, robots.txt)
/seo-rank compare      # Compare two pages for the same keyword
```

## License

MIT
