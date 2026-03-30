# SEO Rank

🌐 [English](README.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Português](README.pt.md) | [Deutsch](README.de.md)

Un skill Claude Code pour des audits SEO complets et une optimisation aux standards 2026. Couvre la qualite du contenu, la performance technique, l'architecture du site, l'explorabilite et les signaux off-page.

Deux frameworks, couverture totale :
- **SEARCH Framework** (SEO de contenu) — Intention de recherche, E-E-A-T, qualite, mots-cles, CTR, structure
- **TECH Framework** (SEO technique) — Core Web Vitals, exploration, rendu, securite, architecture, i18n, accessibilite, donnees structurees, SEO local

## Ce qu'il fait

- Audite les pages et les sites avec des matrices de notation ponderees
- Verifie les Core Web Vitals (LCP, INP, CLS) via Lighthouse CLI
- Valide robots.txt, sitemap.xml, URLs canoniques, balises hreflang
- Audite les en-tetes de securite (HSTS, CSP, X-Frame-Options)
- Analyse le contenu pour les signaux E-E-A-T, la couverture de mots-cles et l'intention de recherche
- Examine les donnees structurees (JSON-LD schema) et genere le balisage manquant
- Produit des recommandations priorisees (gains rapides, effort moyen, strategiques)
- Couvre le SEO international, le chevauchement avec l'accessibilite et le SEO local

## Skill complementaire

Se combine avec [ai-rank](https://github.com/entpnomad/ai-rank) pour une visibilite complete dans les moteurs de recherche :
- **seo-rank** gere le SEO traditionnel + technique sur Google/Bing
- **ai-rank** gere les moteurs de reponse LLM + les agents IA autonomes

Utilisez les deux ensemble pour une couverture totale sur la recherche traditionnelle et la recherche propulsee par l'IA.

## Installation

```bash
git clone https://github.com/entpnomad/seo-rank.git ~/.claude/skills/seo-rank
```

Ou pour un projet specifique :

```bash
git clone https://github.com/entpnomad/seo-rank.git .claude/skills/seo-rank
```

## Utilisation

```
/seo-rank              # Flux complet (audit + recommandations + implementation)
/seo-rank audit        # Audit complet uniquement (scores SEARCH + TECH)
/seo-rank tech         # Audit technique uniquement (CWV, securite, explorabilite)
/seo-rank content      # Audit de contenu uniquement (intention, E-E-A-T, mots-cles)
/seo-rank cwv          # Verification des Core Web Vitals uniquement
/seo-rank headers      # Verification des en-tetes de securite uniquement
/seo-rank schema       # Audit des donnees structurees + generer le JSON-LD manquant
/seo-rank meta         # Audit des title tag, meta description, balises OG
/seo-rank i18n         # Audit SEO international (hreflang, localisation)
/seo-rank local        # Audit SEO local (GBP, NAP, schema local)
/seo-rank checklist    # Checklists complets page + site
/seo-rank site         # Audit au niveau du site (architecture, sitemap, robots.txt)
/seo-rank compare      # Comparer deux pages pour le meme mot-cle
```

## Licence

MIT
