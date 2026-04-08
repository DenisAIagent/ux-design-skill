# UX Design Expert — Claude Code Skill

**v2.0.0** — Skill complet pour Claude Code couvrant le design UI/UX, les stratégies de croissance SaaS, et les interfaces IA. Fonctionne sur n'importe quel site web.

## Commandes

| Commande | Description |
|----------|-------------|
| `/audit <url>` | Audit UX complet avec score /100 et plan d'action priorisé |
| `/landing <url>` | Analyse et optimisation de landing page |
| `/onboarding <url>` | Audit ou conception de flow d'onboarding |
| `/roast <url>` | Critique UX rapide, directe, top 5 problèmes |
| `/compare <url1> <url2>` | Comparaison UX de deux sites concurrents |
| `/flow <description>` | Conception de user flow complet avec wireframes textuels |
| `/copy <element> <context>` | UX writing et micro-copy optimisé (3 variantes) |
| `/checklist <type>` | Checklist UX prête à l'emploi (launch, landing, onboarding, retention, accessibility, mobile, ai, conversion) |
| `/strategy <description>` | Stratégie UX complète (canvas, roadmap, KPIs) |
| `/heuristics <url>` | Évaluation heuristique formelle (Nielsen's 10, score /50) |
| `/persona <description>` | Création de personas utilisateur (P50/P95) |

Sans commande, le skill agit comme consultant UX senior.

## Contenu

### Skill principal (`SKILL.md`)
- 11 commandes documentées avec workflows détaillés
- Masterclass SaaS Growth (6 modules)
- 10 heuristiques de Nielsen
- Design P50/P95 (Nielsen, 2026)
- Intent-Based UX pour l'IA
- Patterns SaaS (onboarding, landing pages, fidélisation)
- Patterns AI interfaces (Wroblewski, Friedman)
- Biais psychologiques (contraste, cadrage, Hick, Fitts, Miller, Jakob, position sérielle)
- Stratégie UX + tendances 2026
- Checklist d'audit UX complète
- Formats de sortie structurés (audit, design, recommandations)

### Base de connaissances (`knowledge-base/`)

| Source | Type | Fichiers |
|--------|------|----------|
| @clea_ux | Transcriptions TikTok (JSON) | 98 |
| UX Tigers | Articles (MD) | 141 |
| Julie Zhuo (lg.substack.com) | Articles (MD) | 49 |
| Jakob Nielsen PhD | Articles (MD) | 33 |
| Femke Design | Videos YT (MD) | 10 |
| NN/g | Articles (MD) | 5 |
| Smashing Magazine | Articles (MD) | 5 |
| Articles cles 2026 | Articles (MD) | 3 |
| Luke Wroblewski | Articles (MD) | 3 |
| Don Norman | Articles (MD) | 3 |

### References synthetisees (`references/`)

- `masterclass-saas-growth.md` — 6 modules complets
- `saas-ux-patterns.md` — Patterns @clea_ux
- `ai-ux-design.md` — Nielsen, Wroblewski, NN/g
- `ux-strategy-trends.md` — Friedman, trends 2026

## Installation

```bash
# Cloner dans le dossier skills
git clone git@github.com:DenisAIagent/ux-design-skill.git ~/.agents/skills/ux-design-expert

# Creer le symlink Claude Code
ln -sf ../../.agents/skills/ux-design-expert ~/.claude/skills/ux-design-expert
```

## Utilisation

Le skill se déclenche automatiquement quand vous parlez de :
- UX audit, onboarding, landing page, conversion
- SaaS UX, fidélisation, rétention, churn
- AI UX, design patterns, heuristic evaluation
- Figma, wireframes, prototypage

Ou invoquez une commande directement : `/audit www.example.com`

### Architecture

```
Utilisateur → /audit www.example.com
       ↓
Claude + SKILL.md (toute la connaissance UX chargée)
       ↓
WebFetch du site → Analyse avec les frameworks → Output structuré
```

Le skill injecte l'expertise UX dans le contexte de Claude. Pas d'agent orchestrateur — Claude applique directement les frameworks (Nielsen, @clea_ux, Zhuo, etc.) avec une vision holistique.

## Sources

- [Jakob Nielsen PhD](https://jakobnielsenphd.substack.com/)
- [Julie Zhuo — The Looking Glass](https://lg.substack.com/)
- [Luke Wroblewski](https://lukew.com/)
- [Don Norman](https://jnd.org/)
- [Nielsen Norman Group](https://www.nngroup.com/articles/)
- [Smashing Magazine](https://www.smashingmagazine.com/)
- [UX Tigers](https://www.uxtigers.com/)
- [@clea_ux](https://www.tiktok.com/@clea_ux)
