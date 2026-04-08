# Intent by Discovery: Designing the AI User Experience

**Date:** 2026-03-26

**Source:** [Original Article](https://jakobnielsenphd.substack.com/p/intent-ux)

---

## Summary

AI fundamentally shifts user roles from operators to supervisors, requiring UX to transition from command-based interaction toward intent-based delegation, new metrics, orchestration layers, calibrated friction, and exploration-based discovery.

## The Paradigm Shift

The most significant aspect of AI interfaces isn't natural language conversation--it's the transformed user role. Computing is evolving from command-based interaction, where users specify procedures, to intent-based outcome specification, where users declare desired results and AI determines the workflow.

Three historical computing eras emerged: batch systems required submitting complete workflows; command-based systems alternated user and computer turns; intent-based systems allow AI to infer and execute workflows autonomously. Users no longer command "how"--they specify "what," and the system figures out the rest.

An effective intent requires three components: desired outcomes, behavioral constraints, and delegation boundaries. A vague request like "plan my Chicago trip" needs clarification about budget, fixed commitments, and whether AI can purchase tickets or merely prepare options.

## Three Eras of UX Goals

**Era 1 (1960-1995): Productivity Focus**
Business computing prioritized learning speed and error reduction. Training budgets represented significant opportunities for usability improvements.

**Era 2 (1995-2025): Influence Focus**
Internet-era design emphasized persuasion--driving purchases, subscriptions, and engagement. This era introduced both dark patterns and manipulative design techniques.

**Era 3 (2026 onward): Augmentation Focus**
AI shifts goals toward expanding human capabilities. "The goal of UX in the AI era is to expand what humans can do and be, not only what we accomplish in software." This encompasses imagination, judgment, and meaning-making beyond software productivity alone.

## The Articulation Barrier Challenge

Current chat-based AI creates severe usability problems through the articulation barrier--roughly half the population struggles with literacy-dependent interfaces. Writing descriptive prose demands greater cognitive effort than reading existing text.

The existence of "prompt engineering" guidance proves this interface fails human-centered design standards. Overcoming this requires prompt augmentation and aided prompt understanding through style galleries and visual selection tools rather than blank-canvas text entry.

Mature systems need visible, editable user models where people inspect, correct, and override AI assumptions about preferences, constraints, tone, and risk tolerance. Memory becomes a primary UX surface.

## Redefining Usability Metrics

Intent-based systems operate probabilistically rather than deterministically, necessitating complete metric reimagining:

- **Intent Capture over Discoverability**: Does the system accurately map vague requests to structured machine actions?

- **Clarification Quality over Error Prevention**: How gracefully does the system handle ambiguity? The best clarifying question prevents the largest mistake with minimal intervention.

- **Ease of Delegation over Time-to-Learn**: How comfortably can users delegate multi-step objectives without catastrophic failure fears? Time-to-correct matters more than learning curves.

- **Verification Efficiency over Execution Efficiency**: Execution becomes cheap; evaluation becomes the bottleneck. "Evaluability" becomes paramount--users must rapidly verify outputs match actual goals.

- **Execution Transparency over System Status Visibility**: The system must project accurate operational plans before and during execution, showing believed user intent and planned next steps.

- **Trust Calibration over User Satisfaction**: Do users rely on agents appropriately? Counterfactual explanations teach decision logic: "Plan A won over B because cost mattered more than speed."

Traditional time-on-task metrics matter less when human contribution is stating intentions. Time-to-correct becomes central. Error counts split into user slips versus system misinterpretations.

## The Triple-Layered Design Model

GUI doesn't disappear--it becomes demoted. Screens shift from where work begins to where work is inspected, negotiated, and corrected.

**Layer 1: Intent Surface**
Highly context-aware, accepting multimodal inputs (voice, text, camera, screen context) to overcome articulation barriers. Advanced systems employ implicit intent inference, proactively offering high-probability intentions for confirmation rather than forcing users to generate prompts from scratch.

**Layer 2: Orchestration Surface**
The critical negotiation layer where agents reveal proposed plans before high-stakes actions, expose data provenance, and seek consent. This provides execution transparency and handles permission choreography. Post-action receipts summarize changes, affected systems, assumptions, and reversibility options.

Critically, this layer manages collaborative intent by flagging conflicting directives from multiple stakeholders and negotiating consensus before execution, particularly important in organizational contexts where personal preference filters through institutional rules.

**Layer 3: Direct-Manipulation Surface**
Traditional GUI remains as fallback for edge-case editing, granular corrections, and emergency overrides. Direct manipulation migrates upward in abstraction--users manipulate plans, dragging tasks through timelines, scrubbing sequences, and reordering itineraries rather than raw controls.

## Supervisory Control and Intentional Friction

The user shifts from driver to chauffeur manager. This demands completely different design principles than command-based interfaces.

For routine, low-stakes tasks, frictionless design remains appropriate. High-stakes tasks (financial transactions, medical decisions, sensitive communications) require intentional slowdowns. Autonomy should be earned progressively through performance demonstration rather than granted immediately.

Progressive delegation provides better alternatives to binary manual versus automated control. Effective agents begin conservatively, drafting and preparing outputs while accumulating performance history, then widening action budgets as reliability becomes evident.

The "Plausibility Trap" describes how synthesized AI answers feel flawlessly authoritative, triggering authority bias that tempts users to skip critical analysis. Combat this through granular authorization, artificial time delays (three-second countdowns), and provenance highlighting ensuring humans remain cognitively responsible.

Friction should be surgical, not blanket. Epistemic UIs visualize the system's uncertainty, highlighting probabilistic leaps, flagging weak-provenance data, and color-coding confidence levels. This directs cognitive effort precisely where judgment matters.

Context-aware friction thresholds reflect user roles, organizational risk tolerance, and action reversibility. A $500 transfer requires high friction in personal banking but represents a frictionless rounding error for corporate finance AI.

## Slow AI and Long-Running Tasks

Powerful AI tools generating videos or conducting deep research can require hours or days. This resurrects "Zombie UX" from batch-processing eras. Extreme delays create intense anxiety about whether AI heads in the right direction.

Design interventions for Slow AI include:

**Run Contracts**: Clear upfront agreements showing estimated timeframes, cost caps, completion definitions, and hard boundaries (e.g., "will not email external parties").

**Conceptual Breadcrumbs**: Short synthesized summaries of intermediate conclusions replace useless percentage bars for 10-hour tasks. Early flawed conclusions allow immediate intervention.

**Context Reboarding**: After 30-hour breaks, users forget original requests. Resumption summaries remind users of initial intent, key decisions, and current status.

**Tiered Notifications**: Critical blocks require immediate push notifications; quality-affecting decisions warrant low-priority emails; task completions get batched digests.

**Progressive Disclosure and Salvage Value**: Long tasks exacerbate sunk-cost fallacies. Progressive disclosure of rough outlines enables early course-correction. Showing "salvage value" (reusable intermediate artifacts) eases psychological pain when restarting.

## Intent by Discovery: Exploring Latent Space

As AI generates thousands of competent solutions rapidly, user needs shift from production toward discovery. Iteration becomes exploration through multidimensional solution spaces rather than error correction.

Current linear UIs relying on back buttons prove inadequate. Future interfaces require multi-branched exploration support. "Intent by discovery" assumes users don't know what they want--help them recognize it progressively through reactions to alternatives, locking in what matters, and exploring adjacent possibilities.

## Future Interaction Paradigms

**Spatial Navigation of Latent Space**
Instead of typing prompts, users navigate interactive 2D maps of generated outputs. Dragging cursors across semantic topographies morphs outputs in real-time. Users discover intent by seamlessly exploring adjacent possibilities, stopping when outputs "feel right." Divergent routing leverages recognition over recall--AI generates edge-case variations while users select better options, iteratively narrowing the possibility space.

**Direct Object Manipulation**
Hybridizing GUI and AI paradigms, users refine intent by physically altering outputs. Dragging a hero image larger doesn't just register coordinates--AI reverse-engineers intent ("user prioritizes visual impact") and automatically adjusts typography, lighting, and secondary elements maintaining coherence. Tactile actions become prompts.

**Socratic Scaffolding**
Systems shift from passive order-takers to active interviewers. Progressive probing presents diagnostic questions or visual counterfactuals rather than hallucinating generic outputs. "Are we optimizing for immediate revenue or long-term brand awareness?" helps users chisel away marble revealing exact intent.

**Ephemeral and Generative UIs**
Interfaces generate dynamically based on emerging context. Detecting music mood exploration or database schema logic, systems spawn bespoke controls (custom sliders, visual node-graphs, reference boards) for that specific discovery moment. Once intent locks, controls dissolve.

**Curation as Intent**
Text communicates inefficiently for complex aesthetics. Intent by discovery leverages multimodal curation--users dump disorganized artifacts (competitor PDFs, color palettes, voice memos) onto digital canvases. Systems organize, find conceptual overlaps, and synthesize starting points. Users discover intent recognizing how AI connects fragmented inspirations.

**Subtractive Sculpting**
Current prompting is additive--users build outcomes through additional words. Discovery works better subtractively. Generate overwhelming maximalist versions, then users delete, strike through, and whittle away unwanted parts. Editing proves infinitely easier than generating from blank screens.

## Designer Role Transformation

Rather than designing linear user flows, designers now architect possibility spaces. They design boundary constraints, latent-space physics, and feedback loops within generative environments. Prompt augmentation provides essential present-moment bridges, but fully embracing intent-by-discovery treats AI as fluid, co-navigational environments where prompting eventually disappears.

Caution: The zero-learning ideal carries hidden costs. If users never learn systems, navigate hierarchies, or make decisions, they suffer cognitive offloading and deskilling, becoming "mere passengers in their digital lives, trapped in a 'Cognitive Atrophy Loop.'" Good AI UX teaches sufficiently, reveals plan structures, and preserves comprehensible action trails maintaining digital judgment.

## Action Items for Designers

- Measure intent capture, not click efficiency, building evaluation frameworks around goal inference accuracy
- Design the orchestration layer--the negotiation surface where trust is built or lost
- Deliberately choreograph friction, mapping task inventory by stakes for high-stakes actions
- Plan for slow tasks from day one, incorporating run contracts, conceptual breadcrumbs, and salvage-value disclosure
- Resist zero-learning traps through systems keeping users cognitively engaged with AI actions and reasoning

Command-based paradigms served magnificently for sixty years, producing genuine intellectual achievements in heuristics and guidelines. However, the world shifts, and UX must shift with it--not abandoning prior knowledge but recognizing that usability definitions themselves are being rewritten.
