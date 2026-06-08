---
type: concept
name: pomdp
related_concepts:
  - world-models
  - reinforcement-learning
  - markov-decision-process
related_entities: []
sources:
  - "[[sources/a-functional-taxonomy-of-world-models]]"
evergreen: false
---

# POMDP

## Definition

POMDP stands for Partially Observable Markov Decision Process. It is a formal framework from reinforcement learning that models how an agent interacts with an environment. In a POMDP, an agent takes actions that affect the state of the world, but the agent never directly observes the state itself. Instead, the agent receives observations (e.g., images, sensor readings) that are partial views of the true underlying state. The agent uses these observations to inform its next actions, creating a loop: agent → action → state → observation → agent.

## Why It Matters

The POMDP framework is foundational to the modern definition of "world model." The term "world model" originated in reinforcement learning and the POMDP tradition, not in generative AI or computer vision. The POMDP loop elegantly captures what world models do: they learn to represent the underlying state of the world and predict how observations change in response to actions. This framework unifies rendering (observation prediction), simulation (state representation), and planning (action selection).

## Variants / Approaches

- **Fully observable** — Agent can see the complete state (MDP)
- **Partially observable** — Agent sees limited observations (POMDP)
- **Belief state** — Agent maintains a distribution over possible states
- **Latent models** — Neural networks learn latent state representations

## Evidence

- [[sources/a-functional-taxonomy-of-world-models]] — Identifies POMDP as the foundational framework for modern "world model" definition; notes use in reinforcement learning textbooks (Sutton and Barto); emphasizes this as the original technical definition before term was "overloaded" by other fields.

## Open Questions

- How do modern neural world models map to POMDP structure?
- Can deep learning efficiently learn belief states in high-dimensional spaces?
- How does the POMDP framework extend to multi-agent and non-stationary environments?

## Contradictions

None identified.
