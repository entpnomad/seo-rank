# SEO Rank

🌐 [English](README.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Português](README.pt.md) | [Deutsch](README.de.md)

Uno skill di Claude Code per audit SEO completi e ottimizzazione secondo gli standard 2026. Copre qualita dei contenuti, prestazioni tecniche, architettura del sito, scansionabilita e segnali off-page.

Due framework, copertura totale:
- **SEARCH Framework** (SEO dei contenuti) — Intento di ricerca, E-E-A-T, qualita, parole chiave, CTR, struttura
- **TECH Framework** (SEO tecnico) — Core Web Vitals, scansione, rendering, sicurezza, architettura, i18n, accessibilita, dati strutturati, SEO locale

## Cosa fa

- Audita pagine e siti con matrici di punteggio ponderate
- Verifica i Core Web Vitals (LCP, INP, CLS) tramite Lighthouse CLI
- Valida robots.txt, sitemap.xml, URL canonici, tag hreflang
- Audita gli header di sicurezza (HSTS, CSP, X-Frame-Options)
- Analizza i contenuti per segnali E-E-A-T, copertura delle parole chiave e intento di ricerca
- Esamina i dati strutturati (JSON-LD schema) e genera il markup mancante
- Produce raccomandazioni prioritizzate (vittorie rapide, sforzo medio, strategiche)
- Copre SEO internazionale, sovrapposizione con l'accessibilita e SEO locale

## Skill complementare

Si combina con [ai-rank](https://github.com/entpnomad/ai-rank) per una visibilita completa nei motori di ricerca:
- **seo-rank** gestisce il SEO tradizionale + tecnico su Google/Bing
- **ai-rank** gestisce i motori di risposta LLM + agenti IA autonomi

Usali insieme per una copertura totale sulla ricerca tradizionale e quella basata sull'IA.

## Installazione

```bash
git clone https://github.com/entpnomad/seo-rank.git ~/.claude/skills/seo-rank
```

O per un progetto specifico:

```bash
git clone https://github.com/entpnomad/seo-rank.git .claude/skills/seo-rank
```

## Utilizzo

```
/seo-rank              # Flusso completo (audit + raccomandazioni + implementazione)
/seo-rank audit        # Solo audit completo (punteggi SEARCH + TECH)
/seo-rank tech         # Solo audit tecnico (CWV, sicurezza, scansionabilita)
/seo-rank content      # Solo audit dei contenuti (intento, E-E-A-T, parole chiave)
/seo-rank cwv          # Solo verifica Core Web Vitals
/seo-rank headers      # Solo verifica header di sicurezza
/seo-rank schema       # Audit dati strutturati + generare JSON-LD mancante
/seo-rank meta         # Audit di title tag, meta description, tag OG
/seo-rank i18n         # Audit SEO internazionale (hreflang, localizzazione)
/seo-rank local        # Audit SEO locale (GBP, NAP, schema locale)
/seo-rank checklist    # Checklist completi pagina + sito
/seo-rank site         # Audit a livello di sito (architettura, sitemap, robots.txt)
/seo-rank compare      # Confrontare due pagine per la stessa parola chiave
```

## Licenza

MIT
