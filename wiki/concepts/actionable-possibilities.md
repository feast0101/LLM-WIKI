---
type: concept
name: Actionable Possibilities
related_concepts:
  - "[[concepts/hypothetical-thinking]]"
  - "[[concepts/world-models]]"
  - "[[concepts/simulative-reasoning]]"
  - "[[concepts/pan-agi]]"
related_entities: []
sources:
  - "[[sources/critiques-of-world-models]]"
evergreen: false
---

# Actionable Possibilities

## Definition

The set of all plausible, goal-relevant future states that an agent can reach through different action sequences. A world model's primary function is to simulate actionable possibilities, enabling agents to reason about which actions will advance their goals. Unlike passive prediction of the next state, actionable possibilities emphasize the relationship between agent actions and environmental outcomes—what futures are achievable and worth pursuing.

## Why It Matters

Defining the goal of world modeling as "simulating all actionable possibilities" reframes the purpose from passive next-step prediction to active agent decision-making. This perspective shifts evaluation from visual fidelity or one-step prediction accuracy to whether the model enables agents to identify and execute action sequences that lead to goal achievement. It emphasizes that world models serve agents first, not observers.

## Variants / Approaches

- **Action-conditioned prediction**: Model how different actions lead to different futures
- **Goal-conditioned simulation**: Simulate paths from current state to goal states
- **Intervention sensitivity**: Assess whether simulated futures respond realistically to different agent interventions
- **Constraint-valid rollouts**: Generate action sequences respecting domain constraints (physical, social, logical)
- **Exploration-exploitation trade-off**: Identify unexplored possible futures worth investigating

## Evidence

- World models designed for agent decision-making must simulate actionable possibilities, not just plausible observations [[sources/critiques-of-world-models]]
- The Dune example illustrates an agent simulating all possible futures (actionable possibilities) to select the best plan [[sources/critiques-of-world-models]]
- Transfer learning works because actionable possibilities in novel domains often share mechanistic structure with training domains [[sources/critiques-of-world-models]]
- [[sources/agentic-world-modeling]] emphasizes decision-centric evaluation, which aligns with actionable-possibilities framing [[sources/agentic-world-modeling]]

## Open Questions

- How can world models efficiently represent and search through the space of actionable possibilities?
- What training objectives best encourage models to learn actionable possibilities rather than mere plausibility?
- How do actionable possibilities differ across physical, digital, social, and scientific domains?
- Can models explicitly represent which futures are achievable vs. unreachable without exhaustive search?

## Contradictions

<!-- Leave blank if none exist. -->
