---
type: concept
name: Simulator (L2 Capability Level)
related_concepts:
  - "[[concepts/predictor]]"
  - "[[concepts/evolver]]"
  - "[[concepts/levels-laws-taxonomy]]"
  - "[[concepts/world-models]]"
  - "[[concepts/renderer]]"
  - "[[concepts/planner]]"
  - "[[concepts/physics-engine]]"
  - "[[concepts/sim-to-real]]"
  - "[[concepts/physical-law]]"
  - "[[concepts/digital-law]]"
  - "[[concepts/social-law]]"
  - "[[concepts/scientific-law]]"
related_entities:
  - "[[entities/World-Labs]]"
  - "[[entities/NVIDIA]]"
sources:
  - "[[sources/a-functional-taxonomy-of-world-models]]"
  - "[[sources/agentic-world-modeling]]"
evergreen: false
---

# Simulator (L2 Capability Level)

## Definition

A simulator is both (1) a type of world model that outputs state—a geometrically, physically, and dynamically faithful representation that both humans and computer programs can compute on—and (2) the second capability level (L2) in the agentic world modeling hierarchy. Unlike renderers (which optimize for visual appearance), simulators prioritize structural accuracy: geometry that holds up under inspection, physics that respects Newton's laws, dynamics that reflect how the world behaves, and action-conditioned rollouts that compose one-step transitions into multi-step trajectories while respecting domain-specific governing laws (physical, digital, social, scientific).

## Why It Matters

Simulators are the linchpin of world model research, both functionally and in the capability hierarchy. They serve two critical audiences: (1) human professionals (architects, designers, engineers) who need accuracy beyond visual plausibility, and (2) embodied AI systems (robots, autonomous vehicles, RL agents) that use simulators as training grounds. At L2, simulators enable multi-step planning and look-ahead reasoning—critical for agent decision-making. A model that masters L2 simulation can project its understanding both into pixels (rendering) and into action predictions (planning), enabling closed-loop agentic control.

## Variants / Approaches

- **Physics-conditioned simulators** — Enforce Newton's laws and dynamics; used in robotics, manipulation, autonomous driving
- **Generative simulators** — Learned models generating physically plausible dynamics while maintaining constraint satisfaction
- **Multimodal input simulators** — Accept text, images, video, spatial sketches; generate 3D environments with both visual and state outputs
- **Digital-law simulators** — Model program semantics and UI dynamics; used in web agents and software tool use
- **Social-interactive simulators** — Model agent beliefs, goals, norms; used in multi-agent social simulation
- **Scientific-mechanistic simulators** — Enforce causal structure and experimental observables; used in AI for science discovery

## Evidence

- [[sources/a-functional-taxonomy-of-world-models]] — Defines simulator as the second functional category and the linchpin; notes simulators demand geometry, physics, and dynamics; discusses Marble as bridging renderer and simulator [[sources/a-functional-taxonomy-of-world-models]]
- [[sources/agentic-world-modeling]] — Formalizes simulators as L2 capability level, composing transitions into multi-step rollouts respecting domain laws [[sources/agentic-world-modeling]]
- Model-based RL systems (DayDreamer, MuZero, TD-MPC2, OccWorld) instantiate L2 capabilities through imagination rollouts [[sources/agentic-world-modeling]]
- Web agents (WebDreamer, SWE-agent) and GUI navigation require digital-law simulators [[sources/agentic-world-modeling]]

## Open Questions

- How are constraint satisfaction and multi-step coherence best enforced: via architecture, training objectives, or post-hoc interventions?
- What is the relationship between simulator accuracy and downstream agent performance across different governing-law regimes?
- Can a single architecture support multi-step simulation across physical, digital, social, and scientific domains?
- How can we close the sim-to-real gap for reliable real-world deployment?
- What is the minimal training signal for a simulator to learn representations useful for agent planning?

## Contradictions

<!-- Leave blank if none exist. -->
