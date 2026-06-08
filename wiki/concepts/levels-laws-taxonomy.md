---
type: concept
name: Levels × Laws Taxonomy
related_concepts:
  - "[[concepts/predictor]]"
  - "[[concepts/simulator]]"
  - "[[concepts/evolver]]"
  - "[[concepts/physical-law]]"
  - "[[concepts/digital-law]]"
  - "[[concepts/social-law]]"
  - "[[concepts/scientific-law]]"
  - "[[concepts/world-models]]"
related_entities: []
sources:
  - "[[sources/agentic-world-modeling]]"
evergreen: false
---

# Levels × Laws Taxonomy

## Definition

A two-axis organizational framework for understanding agentic world modeling capabilities. The first axis defines three **capability levels**: L1 Predictor (one-step local transitions), L2 Simulator (multi-step rollouts respecting domain laws), L3 Evolver (autonomous model revision with new evidence). The second axis identifies four **governing-law regimes**: Physical (objects, forces, dynamics), Digital (program semantics, logic), Social (beliefs, norms, coordination), and Scientific (causal mechanisms, experiments).

## Why It Matters

The Levels × Laws taxonomy addresses conceptual fragmentation across research communities. Historically, world models have been evaluated differently depending on discipline: vision researchers by visual fidelity, RL practitioners by task performance, roboticists by real-world applicability, social scientists by behavioral realism, and scientists by discovery success. This taxonomy provides a common language while preserving domain-specific differences. It clarifies capability progression (what must a system do to advance from L1 to L2 to L3?) and distinguishes where failure modes arise (failures in physical worlds differ fundamentally from failures in social or scientific worlds).

## Variants / Approaches

- **Modality-agnostic framing**: Rather than organizing by visual/text/3D modality, organize by capability and constraint
- **Decision-centric evaluation**: Evaluate world models by whether they enable effective agent planning, not by visual metrics alone
- **Cross-domain synthesis**: Unify previously isolated communities (embodied AI, generative models, web agents, multi-agent systems, AI for science) under a common framework
- **Regime-specific instantiation**: Recognize that L1/L2/L3 manifest differently in physical vs. digital vs. social vs. scientific domains

## Evidence

- [[sources/agentic-world-modeling]] introduces the Levels × Laws taxonomy synthesizing over 400 works spanning model-based RL, video generation, web/GUI agents, multi-agent simulation, and scientific discovery [[sources/agentic-world-modeling]]
- The taxonomy subsumes previous domain-specific frameworks (e.g., visual generation taxonomy G1–G4) while providing complementary capability-centric organization [[sources/agentic-world-modeling]]
- Specific systems are positioned within the 3×4 grid: DayDreamer (L2, Physical); WebDreamer (L2, Digital); AI Scientist (L3, Scientific) [[sources/agentic-world-modeling]]
- The framework clarifies boundary conditions between levels (multi-step coherence, constraint satisfaction, model updating) and identifies failure modes by regime [[sources/agentic-world-modeling]]

## Open Questions

- How rigid are the boundaries between L1, L2, and L3? Can systems be partially at one level?
- Are there meaningful systems at L3 in physical, digital, and social domains, or is L3 primarily scientific?
- How do hybrid systems (e.g., simulators that occasionally invoke revision) fit within the hierarchy?
- What architectural patterns generalize across the L1–L3 spectrum and across the four law regimes?
- How can the Levels × Laws taxonomy integrate with other organizing principles (architecture, training objectives, evaluation metrics)?

## Contradictions

- [[sources/critiques-of-world-models]] proposes hierarchical, nested representations as essential for general-purpose world models, suggesting that representational hierarchy may be orthogonal to or interact with the Levels × Laws capability hierarchy [[sources/critiques-of-world-models]]. The precise relationship remains underspecified.

