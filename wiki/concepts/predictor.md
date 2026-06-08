---
type: concept
name: Predictor (L1 Capability Level)
related_concepts:
  - "[[concepts/simulator]]"
  - "[[concepts/evolver]]"
  - "[[concepts/levels-laws-taxonomy]]"
  - "[[concepts/world-models]]"
related_entities: []
sources:
  - "[[sources/agentic-world-modeling]]"
evergreen: false
---

# Predictor (L1 Capability Level)

## Definition

The first and most basic capability level in agentic world modeling. An L1 Predictor learns one-step, local transition operators that map from a current state and action to a predicted next state. It performs single-step forward prediction without composing transitions into multi-step rollouts or enforcing domain-specific constraints.

## Why It Matters

L1 is the foundational capability upon which higher-level simulators and evolvers are built. Understanding predictors in isolation clarifies what capabilities are insufficient for agent planning and decision-making, and what additional machinery (constraint validation, closed-loop composition) is required to move toward operational world models.

## Variants / Approaches

- **Latent space predictors**: Learn transition dynamics in a learned latent representation rather than pixel space
- **Action-conditioned video prediction**: Predict the next frame given current observation and an action
- **State-space prediction**: Predict the next state vector given current state and action
- **Observation decoders**: Map from latent state predictions back to observable outputs
- **Inverse dynamics models**: Infer the action taken given observed state transition

## Evidence

- Model-based reinforcement learning systems historically started with one-step predictors before scaling to multi-step imagination [[sources/agentic-world-modeling]]
- Video generation models like early action-conditioned variants operate at the L1 level, predicting plausible next frames without enforcing physical or geometric consistency [[sources/agentic-world-modeling]]
- The distinction between L1 and L2 hinges on whether a model can compose predictions into valid multi-step rollouts [[sources/agentic-world-modeling]]

## Open Questions

- What is the minimal training signal required for an L1 predictor to learn representations useful for downstream planning?
- How does accuracy degradation compound over multiple one-step predictions without closed-loop correction?
- Can L1 predictors be augmented with simple heuristics to approach L2 capabilities without full constraint validation?
- What role does action conditioning play in determining whether a predictor supports agent decision-making?

## Contradictions

<!-- Leave blank if none exist. -->
