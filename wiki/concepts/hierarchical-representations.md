---
type: concept
name: Hierarchical Representations
related_concepts:
  - "[[concepts/world-models]]"
  - "[[concepts/pan-agi]]"
  - "[[concepts/generative-learning]]"
  - "[[concepts/hypothetical-thinking]]"
related_entities: []
sources:
  - "[[sources/critiques-of-world-models]]"
evergreen: false
---

# Hierarchical Representations

## Definition

Multi-level representational structures in world models where abstract, high-level concepts (goals, plans, strategies) are built on top of concrete, low-level details (pixels, joint positions, actions). Hierarchical representations enable reasoning at multiple levels of abstraction—immediate sensorimotor control, tactical planning, and strategic reasoning—within a unified cognitive architecture.

## Why It Matters

Humans operate through hierarchies of abilities: immediate (body control, movement), intermediate (reading, speaking, drawing), and abstract (planning, collaboration, strategy). A single human brain executes household chores, scientific research, and diplomatic negotiation using the same cognitive architecture. Hierarchical representations in AI systems aim to achieve similar generality by enabling reasoning at appropriate levels of abstraction for different tasks. This contrasts with flat representations optimized for a single level (e.g., pixel-space prediction or high-level goal specification).

## Variants / Approaches

- **Multi-scale temporal modeling**: Predict at different timescales (immediate next action, 10-step plans, long-horizon strategies)
- **Abstraction hierarchies**: Learn representations at increasing levels of abstraction (pixels → objects → scenes → goals)
- **Hierarchical RL**: Learn value functions and policies at multiple levels of abstraction
- **Recursive world models**: Apply world modeling at multiple levels, with higher levels predicting over lower-level trajectories
- **Mixed discrete-continuous representations**: Handle both continuous dynamics (physics) and discrete structure (goals, plans)

## Evidence

- PAN AGI emphasizes hierarchical, multi-level representations as essential for general-purpose intelligence [[sources/critiques-of-world-models]]
- Humans exhibit hierarchical cognitive architecture spanning immediate to abstract abilities [[sources/critiques-of-world-models]]
- Some RL systems (hierarchical RL, options framework) instantiate hierarchical representations [[sources/critiques-of-world-models]]
- Multi-scale video prediction models suggest benefits of predicting at multiple temporal scales [[sources/critiques-of-world-models]]

## Open Questions

- How are appropriate levels of abstraction determined for a given domain or task?
- What is the relationship between hierarchical representations and the Levels × Laws taxonomy's capability levels?
- Can hierarchies be learned end-to-end or do they require explicit architectural support?
- How do continuous (dynamics) and discrete (logic, planning) components integrate in hierarchical systems?
- What training signals guide the emergence of meaningful hierarchies?

## Contradictions

- [[sources/agentic-world-modeling]] abstracts away from representational details (including hierarchical structure) to focus on capability levels and governing laws. The relationship between hierarchical representations and capability-level progression (L1→L2→L3) remains unclear [[sources/agentic-world-modeling]].

