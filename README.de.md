# SEO Rank

🌐 [English](README.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Português](README.pt.md) | [Deutsch](README.de.md)

Ein Claude Code Skill fuer umfassende SEO-Audits und Optimierung nach den Standards von 2026. Deckt Content-Qualitaet, technische Performance, Site-Architektur, Crawlbarkeit und Off-Page-Signale ab.

Zwei Frameworks, volle Abdeckung:
- **SEARCH Framework** (Content SEO) — Suchintention, E-E-A-T, Qualitaet, Keywords, CTR, Struktur
- **TECH Framework** (Technisches SEO) — Core Web Vitals, Crawling, Rendering, Sicherheit, Architektur, i18n, Barrierefreiheit, strukturierte Daten, lokales SEO

## Was es macht

- Prueft Seiten und Sites anhand gewichteter Bewertungsmatrizen
- Checkt Core Web Vitals (LCP, INP, CLS) ueber Lighthouse CLI
- Validiert robots.txt, sitemap.xml, kanonische URLs, hreflang-Tags
- Prueft Sicherheits-Header (HSTS, CSP, X-Frame-Options)
- Analysiert Inhalte auf E-E-A-T-Signale, Keyword-Abdeckung und Suchintention
- Untersucht strukturierte Daten (JSON-LD schema) und generiert fehlendes Markup
- Erstellt priorisierte Empfehlungen (Quick Wins, mittlerer Aufwand, strategisch)
- Deckt internationales SEO, Ueberschneidung mit Barrierefreiheit und lokales SEO ab

## Begleit-Skill

Kombiniert sich mit [ai-rank](https://github.com/entpnomad/ai-rank) fuer vollstaendige Suchsichtbarkeit:
- **seo-rank** deckt klassisches + technisches SEO bei Google/Bing ab
- **ai-rank** deckt LLM-Antwortmaschinen + autonome KI-Agenten ab

Nutze beide zusammen fuer volle Abdeckung ueber traditionelle und KI-gestuetzte Suche.

## Installation

```bash
git clone https://github.com/entpnomad/seo-rank.git ~/.claude/skills/seo-rank
```

Oder fuer ein bestimmtes Projekt:

```bash
git clone https://github.com/entpnomad/seo-rank.git .claude/skills/seo-rank
```

## Nutzung

```
/seo-rank              # Vollstaendiger Workflow (Audit + Empfehlungen + Umsetzung)
/seo-rank audit        # Nur vollstaendiges Audit (SEARCH + TECH Scores)
/seo-rank tech         # Nur technisches Audit (CWV, Sicherheit, Crawlbarkeit)
/seo-rank content      # Nur Content-Audit (Intention, E-E-A-T, Keywords)
/seo-rank cwv          # Nur Core Web Vitals Check
/seo-rank headers      # Nur Sicherheits-Header Check
/seo-rank schema       # Audit strukturierter Daten + fehlendes JSON-LD generieren
/seo-rank meta         # Audit von Title Tag, Meta Description, OG Tags
/seo-rank i18n         # Internationales SEO Audit (hreflang, Lokalisierung)
/seo-rank local        # Lokales SEO Audit (GBP, NAP, lokales Schema)
/seo-rank checklist    # Vollstaendige Seiten- + Site-Checklisten
/seo-rank site         # Site-Level Audit (Architektur, Sitemap, robots.txt)
/seo-rank compare      # Zwei Seiten fuer dasselbe Keyword vergleichen
```

## Lizenz

MIT
