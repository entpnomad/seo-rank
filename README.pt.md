# SEO Rank

🌐 [English](README.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Português](README.pt.md) | [Deutsch](README.de.md)

Um skill de Claude Code para auditorias SEO completas e otimizacao segundo os padroes de 2026. Cobre qualidade de conteudo, desempenho tecnico, arquitetura do site, rastreabilidade e sinais off-page.

Dois frameworks, cobertura total:
- **SEARCH Framework** (SEO de conteudo) — Intencao de busca, E-E-A-T, qualidade, palavras-chave, CTR, estrutura
- **TECH Framework** (SEO tecnico) — Core Web Vitals, rastreamento, renderizacao, seguranca, arquitetura, i18n, acessibilidade, dados estruturados, SEO local

## O que faz

- Audita paginas e sites com matrizes de pontuacao ponderadas
- Verifica Core Web Vitals (LCP, INP, CLS) via Lighthouse CLI
- Valida robots.txt, sitemap.xml, URLs canonicas, tags hreflang
- Audita cabecalhos de seguranca (HSTS, CSP, X-Frame-Options)
- Analisa conteudo em busca de sinais E-E-A-T, cobertura de palavras-chave e intencao de busca
- Examina dados estruturados (JSON-LD schema) e gera a marcacao em falta
- Produz recomendacoes priorizadas (ganhos rapidos, esforco medio, estrategicas)
- Cobre SEO internacional, sobreposicao com acessibilidade e SEO local

## Skill complementar

Combina com [ai-rank](https://github.com/entpnomad/ai-rank) para visibilidade completa nos motores de busca:
- **seo-rank** cobre SEO tradicional + tecnico no Google/Bing
- **ai-rank** cobre motores de resposta LLM + agentes de IA autonomos

Usa os dois juntos para cobertura total em busca tradicional e busca potenciada por IA.

## Instalacao

```bash
git clone https://github.com/entpnomad/seo-rank.git ~/.claude/skills/seo-rank
```

Ou para um projeto especifico:

```bash
git clone https://github.com/entpnomad/seo-rank.git .claude/skills/seo-rank
```

## Utilizacao

```
/seo-rank              # Fluxo completo (auditoria + recomendacoes + implementacao)
/seo-rank audit        # Apenas auditoria completa (pontuacoes SEARCH + TECH)
/seo-rank tech         # Apenas auditoria tecnica (CWV, seguranca, rastreabilidade)
/seo-rank content      # Apenas auditoria de conteudo (intencao, E-E-A-T, palavras-chave)
/seo-rank cwv          # Apenas verificacao de Core Web Vitals
/seo-rank headers      # Apenas verificacao de cabecalhos de seguranca
/seo-rank schema       # Auditoria de dados estruturados + gerar JSON-LD em falta
/seo-rank meta         # Auditoria de title tag, meta description, tags OG
/seo-rank i18n         # Auditoria de SEO internacional (hreflang, localizacao)
/seo-rank local        # Auditoria de SEO local (GBP, NAP, schema local)
/seo-rank checklist    # Checklists completas de pagina + site
/seo-rank site         # Auditoria ao nivel do site (arquitetura, sitemap, robots.txt)
/seo-rank compare      # Comparar duas paginas para a mesma palavra-chave
```

## Licenca

MIT
