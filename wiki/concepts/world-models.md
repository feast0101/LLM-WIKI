---
type: concept
name: world-models
related_concepts:
  - renderer
  - simulator
  - planner
  - spatial-intelligence
  - physics-engine
related_entities:
  - "[[entities/World-Labs]]"
  - "[[entities/Fei-Fei-Li]]"
sources:
  - "[[sources/a-functional-taxonomy-of-world-models]]"
  - "[[sources/from-words-to-worlds-spatial-intelligence]]"
evergreen: false
---

# World Models

## Definition

A world model is a learned representation of the statistical structure of space and time that enables an AI system to understand, simulate, and reason about physical or virtual environments. World models learn how light falls on surfaces, how objects move and respond to force, and how dynamics unfold under physical laws. They stand in contrast to language models, which learn the statistical structure of text.

## Why It Matters

World models are the foundation for artificial systems that can genuinely understand and interact with the physical world. They bridge the gap between abstract symbolic reasoning (what language models do) and embodied, sensorimotor intelligence (what agents need to act in the world). World models are considered AI's next frontier after the era of language model dominance, essential for spatial intelligence and eventual artificial general intelligence.

## Variants / Approaches

The field has converged on three functional categories of world models:

- **Renderers** — Output pixels for human consumption; optimize for visual fidelity. Examples: text-to-video models, Google Genie 3.
- **Simulators** — Output state; provide geometrically and physically faithful representations. Enable both human professionals (architects, designers) and AI systems (robots, agents) to compute on and interact with the world.
- **Planners** — Output actions; decide what an agent should do given observations and goals. Examples: Vision-Language-Action models, embodied action models.

These three are increasingly blurring together into unified foundation models that can switch between output modalities.

## Evidence

- [[sources/a-functional-taxonomy-of-world-models]] — Foundational taxonomy distinguishing renderers, simulators, and planners; argues simulators are the linchpin.
- [[sources/from-words-to-worlds-spatial-intelligence]] — Positions spatial intelligence (grounded in world models) as AI's next frontier; contrasts with language models' lack of grounding.

## Open Questions

- What architectural choices best unify rendering, simulation, and planning?
- How can sim-to-real transfer be improved for robust real-world deployment?
- What training data will be needed to scale world models to human-level spatial reasoning?
- How will world models integrate with language models for truly embodied AI?

## Contradictions

None identified.
