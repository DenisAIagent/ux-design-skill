# AI UX Design — Comprehensive Reference

Sources: Jakob Nielsen (33 articles + UX Tigers), NN/g (5 articles), Luke Wroblewski, Vitaly Friedman (2023-2026)

## 1. INTENT-BASED DESIGN (Nielsen, 2026)

### The Paradigm Shift
- AI = first major UI paradigm change in 60 years
- Users shift from **operators** to **supervisors**
- "Intent-based" replaces "command-based"

### Three-Layer Model
1. **Intent Surface** — Multimodal input, implicit intent inference
2. **Orchestration Surface** — Trust-building negotiation layer (plans, provenance, stakeholders)
3. **Direct-Manipulation Surface** — Traditional GUI as fallback

### New Usability Metrics
| Old Metric | New Metric |
|-----------|-----------|
| Discoverability | Intent Capture Accuracy |
| Error Prevention | Clarification Quality |
| Time-to-Learn | Ease of Delegation |
| Execution Efficiency | Verification Efficiency |
| System Status Visibility | Execution Transparency |
| User Satisfaction | Trust Calibration |

- **Time-to-correct** replaces time-on-task as central metric
- Error counts split into user slips vs system misinterpretations

---

## 2. CALIBRATED FRICTION & TRUST

- **Progressive delegation** — Agents begin conservatively, widen action budgets as reliability proves out
- **The Plausibility Trap** — AI answers feel authoritative → triggers authority bias. Combat with granular authorization, artificial delays, provenance highlighting
- **Surgical friction** — Context-aware, not blanket ($500 transfer = high friction personal banking, frictionless corporate)
- **Epistemic UIs** — Visualize uncertainty: highlight probabilistic leaps, flag weak-provenance data, color-code confidence levels
- **Run Contracts** — For long-running AI tasks: estimated time, cost caps, completion definitions, hard boundaries

---

## 3. SLOW AI DESIGN PATTERNS

Long-running AI tasks (hours/days) create "Zombie UX":
- **Conceptual Breadcrumbs** — Synthesized summaries of intermediate conclusions (not percentage bars)
- **Context Reboarding** — After 30+ hour breaks, resumption summaries
- **Tiered Notifications** — Critical = immediate push; quality-affecting = low-priority email; completions = batched
- **Progressive Disclosure** — Show rough outlines early for course-correction
- **Salvage Value** — Display reusable intermediate artifacts

---

## 4. INTENT BY DISCOVERY

- Users don't know what they want → help them recognize it progressively
- **Spatial navigation** — Interactive 2D maps of generated outputs
- **Direct object manipulation** — Dragging hero image larger → AI infers "user prioritizes visual impact"
- **Socratic scaffolding** — Systems shift from passive to active interviewers
- **Ephemeral UIs** — Interfaces generate dynamically for specific discovery moments
- **Subtractive sculpting** — Generate maximalist versions, users delete/whittle down
- **Curation as intent** — Users dump artifacts, AI organizes and synthesizes

---

## 5. DURABLE AI PATTERNS (Wroblewski, 2026)

### Evolution Stages
1. Behind-the-scenes AI (invisible improvements)
2. Direct conversational interaction (chat-dominant)
3. Agentic systems (tool-using, self-directed)

### Proven Patterns
- **Suggested Questions** — Help users understand capabilities
- **Citation Integration** — Sources boost trust significantly
- **Multimedia Responses** — Mix text + images + diagrams
- **Collapsed Tool Calls** — Optional expansion for transparency
- **Split Panels** — Reasoning (left) | Results (right)

### Capability Awareness
- Prompt enhancement (system rewrites user input)
- Visual task builders (compose from capability columns)
- Intelligent onboarding (AI handles empty states)

---

## 6. AI INTERFACE PATTERNS (Friedman, 2025)

### 5 Core Areas
1. **Input UX** — Pre-prompts, node editors, canvas
2. **Output UX** — Contextual visualization
3. **Refinement UX** — Sliders, targeted prompts
4. **AI Actions** — Delegation with suggested actions
5. **AI Integration** — Embed in existing workflows

**Core Principle: "AI-second, not AI-first"** — Enhance existing workflows, don't replace them.

---

## 7. PROMPT AUGMENTATION (Nielsen)

Six UX patterns to overcome the articulation barrier:
1. Style Galleries
2. Prompt Rewrite
3. Targeted Prompt Rewrite
4. Related Prompts
5. Prompt Builders (GUI components)
6. Parametrization

The articulation barrier: prose prompts hurt usability for ~50% of the population.

---

## 8. GENERATIVE UI (Nielsen, 2026)

- Static interfaces become obsolete → bespoke interfaces in real-time
- Users prefer custom AI interfaces over regular websites 90% of the time
- Human designers still win by a hair, but AI improves exponentially
- UX shifts to specifying behavioral constraints, not designing screens
- WIMP (Window, Icon, Menu, Pointer) era ending

### GenUI vs Vibe Coding (NN/g)
- **GenUI** — AI decides to create interface → risk of poor judgment
- **Vibe coding** — Human requests → risk of poor execution
- GenUI benefits users who can't articulate needs

---

## 9. AI AGENTS

### Definition (NN/g, 2026)
"An AI agent pursues a goal by iteratively taking actions, evaluating progress, and deciding its own next steps."

### Components
Goal pursuit + iteration + action + evaluation + self-direction

### Design Implications
- Progressive delegation over binary control
- Gatekeeper Agents — User-side agents screen vendor AI
- Five Levels of Agentic Commerce (Stripe): basic automation → anticipatory purchasing
- **Review Paradox** — Auditing AI work is cognitively harder than doing it yourself

---

## 10. CHATBOT UX (NN/g, 2026)

### Where Chatbots Succeed
- Product-specific Q&A on detail pages
- Complex, context-dependent questions
- Unexpected insights users wouldn't find independently

### Where Chatbots Fail
- Low discoverability, skepticism, unclear value
- Replicating existing search/filter functionality
- Generic openings

**Rule: Research user problems BEFORE implementing chatbot**

---

## 11. AI MATURITY MODEL (6 Levels)

| Level | Name | Characteristics |
|-------|------|----------------|
| 1 | Limited | AI for admin only |
| 2 | Reactive | Ad-hoc experimentation |
| 3 | Developing | Problem-led adoption |
| 4 | Embedded | Deep design-engineering alignment |
| 5 | Leading | Designers work in code via vibe coding |
| 6 | Symbiotic | Design-time/runtime dissolves |

---

## 12. P50/P95 DESIGN (Nielsen)

- Digital engagement follows **power-law distributions**, not bell curves
- The "average user" is a mathematical ghost
- **P50 "Tourist"**: passive, high friction aversion, 16% feature adoption
- **P95 "Whale"**: drives revenue, 45%+ feature adoption
- **Action**: Track P25/P50/P75/P95 instead of means
- **"Fattening the tail"**: Convert P50 → P95 through progressive disclosure and expert pathways

---

## 13. KEY CONCEPTS GLOSSARY

- **AI Sandwich**: Human direction → AI generation → Human curation
- **Articulation Barrier**: Difficulty expressing intent in text prompts
- **Calibrated Trust**: Appropriate skepticism balanced with adoption
- **CORE**: Create Once, Remix Everywhere
- **Navigation Tax**: Time/effort browsing traditional menus
- **Plausibility Trap**: AI answers feel authoritative, tempting to skip analysis
- **Run Contract**: Upfront agreement for long AI tasks
- **Zombie UX**: Batch-era UX problems returning in slow-AI contexts
