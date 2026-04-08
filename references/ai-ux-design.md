# AI UX Design — Reference

Sources: Jakob Nielsen, Luke Wroblewski, NN/g, Vitaly Friedman (2025-2026)

## Intent-Based Design (Nielsen, 2026)

### The Paradigm Shift
- AI = first major UI paradigm change in 60 years
- Users shift from operators to supervisors
- "Intent-based" replaces "command-based"

### Three-Layer Model
1. **Intent Surface** — Multimodal input, implicit intent inference
2. **Orchestration Surface** — Trust-building negotiation layer (plans, provenance, stakeholders)
3. **Direct-Manipulation Surface** — Traditional GUI as fallback

### New Usability Metrics
- Intent capture accuracy
- Clarification quality
- Ease of delegation
- Verification efficiency
- Execution transparency
- Trust calibration

### Calibrated Friction
- Deliberate friction for high-stakes decisions
- Prevents automation bias
- Artificial delays, granular authorization, epistemic UIs

### Slow AI Design Patterns
- Run contracts (clarification upfront)
- Conceptual breadcrumbs (progress summaries)
- Context reboarding (resumption after breaks)
- Tiered notifications
- Visible salvage value of partial results

## Durable AI Patterns (Wroblewski, 2026)

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
- Visual task builders (compose instructions from capability columns)
- Intelligent onboarding (AI handles empty states)

## AI Interface Patterns (Friedman, 2025)

### 5 Core Areas
1. Input UX — Pre-prompts, node editors, canvas
2. Output UX — Contextual visualization
3. Refinement UX — Sliders, targeted prompts
4. AI Actions — Delegation with suggested actions
5. AI Integration — Embed in existing workflows

### Core Principle
**"AI-second, not AI-first"** — Enhance existing workflows, don't replace them.

## GenUI vs Vibe Coding (NN/g, 2026)
- GenUI: AI decides to create interface → risk of poor judgment
- Vibe coding: Human requests → risk of poor execution
- GenUI benefits users who can't articulate needs

## Chatbot UX (NN/g, 2026)
- Most site chatbots fail: low discoverability, skepticism, unclear value
- Success: product-specific Q&A, complex contextual questions, unexpected insights
- Rule: Research user problems BEFORE implementing chatbot

## AI Agent Definition (NN/g, 2026)
"An AI agent pursues a goal by iteratively taking actions, evaluating progress, and deciding its own next steps."

Components: goal pursuit + iteration + action + evaluation + self-direction
