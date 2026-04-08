# UX Design Expert — Claude Code Skill

Skill complet pour Claude Code couvrant le design UI/UX, les strategies de croissance SaaS, et les interfaces IA.

## Contenu

### Skill principal (`SKILL.md`)
- Masterclass SaaS Growth (6 modules)
- 10 heuristiques de Nielsen
- Design P50/P95
- Intent-Based UX pour l'IA
- Patterns SaaS (onboarding, landing pages, fidelisation)
- Patterns AI interfaces
- Biais psychologiques (contraste, cadrage, Hick, Fitts, Miller, Jakob, position serielle)
- Strategie UX + tendances 2026
- Checklist d'audit UX
- Formats de sortie structures

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

Le skill se declenche automatiquement quand vous parlez de :
- UX audit, onboarding, landing page, conversion
- SaaS UX, fidelisation, retention, churn
- AI UX, design patterns, heuristic evaluation
- Figma, wireframes, prototypage

Ou invoquez-le directement : `/ux-design-expert`

## Sources

- [Jakob Nielsen PhD](https://jakobnielsenphd.substack.com/)
- [Julie Zhuo — The Looking Glass](https://lg.substack.com/)
- [Luke Wroblewski](https://lukew.com/)
- [Don Norman](https://jnd.org/)
- [Nielsen Norman Group](https://www.nngroup.com/articles/)
- [Smashing Magazine](https://www.smashingmagazine.com/)
- [UX Tigers](https://www.uxtigers.com/)
- [@clea_ux](https://www.tiktok.com/@clea_ux)
