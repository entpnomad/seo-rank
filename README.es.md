# SEO Rank

🌐 [English](README.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Português](README.pt.md) | [Deutsch](README.de.md)

Un skill de Claude Code para auditorias SEO completas y optimizacion segun los estandares de 2026. Cubre calidad de contenido, rendimiento tecnico, arquitectura del sitio, rastreabilidad y senales off-page.

Dos frameworks, cobertura total:
- **SEARCH Framework** (SEO de contenido) — Intencion de busqueda, E-E-A-T, calidad, palabras clave, CTR, estructura
- **TECH Framework** (SEO tecnico) — Core Web Vitals, rastreo, renderizado, seguridad, arquitectura, i18n, accesibilidad, datos estructurados, SEO local

## Que hace

- Audita paginas y sitios con matrices de puntuacion ponderadas
- Verifica Core Web Vitals (LCP, INP, CLS) via Lighthouse CLI
- Valida robots.txt, sitemap.xml, URLs canonicas, etiquetas hreflang
- Audita cabeceras de seguridad (HSTS, CSP, X-Frame-Options)
- Analiza contenido en busca de senales E-E-A-T, cobertura de palabras clave e intencion de busqueda
- Revisa datos estructurados (JSON-LD schema) y genera el marcado faltante
- Produce recomendaciones priorizadas (victorias rapidas, esfuerzo medio, estrategicas)
- Cubre SEO internacional, solapamiento con accesibilidad y SEO local

## Skill complementario

Se combina con [ai-rank](https://github.com/entpnomad/ai-rank) para visibilidad completa en buscadores:
- **seo-rank** cubre SEO tradicional + tecnico en Google/Bing
- **ai-rank** cubre motores de respuesta LLM + agentes de IA autonomos

Usa ambos juntos para cobertura total en busqueda tradicional y busqueda potenciada por IA.

## Instalacion

```bash
git clone https://github.com/entpnomad/seo-rank.git ~/.claude/skills/seo-rank
```

O para un proyecto especifico:

```bash
git clone https://github.com/entpnomad/seo-rank.git .claude/skills/seo-rank
```

## Uso

```
/seo-rank              # Flujo completo (auditoria + recomendaciones + implementacion)
/seo-rank audit        # Solo auditoria completa (puntuaciones SEARCH + TECH)
/seo-rank tech         # Solo auditoria tecnica (CWV, seguridad, rastreabilidad)
/seo-rank content      # Solo auditoria de contenido (intencion, E-E-A-T, palabras clave)
/seo-rank cwv          # Solo verificacion de Core Web Vitals
/seo-rank headers      # Solo verificacion de cabeceras de seguridad
/seo-rank schema       # Auditoria de datos estructurados + generar JSON-LD faltante
/seo-rank meta         # Auditoria de title tag, meta description, etiquetas OG
/seo-rank i18n         # Auditoria de SEO internacional (hreflang, localizacion)
/seo-rank local        # Auditoria de SEO local (GBP, NAP, schema local)
/seo-rank checklist    # Checklists completos de pagina + sitio
/seo-rank site         # Auditoria a nivel de sitio (arquitectura, sitemap, robots.txt)
/seo-rank compare      # Comparar dos paginas para la misma palabra clave
```

## Licencia

MIT
