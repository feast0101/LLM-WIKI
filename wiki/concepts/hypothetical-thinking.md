---
type: concept
name: Hypothetical Thinking
related_concepts:
  - "[[concepts/world-models]]"
  - "[[concepts/simulative-reasoning]]"
  - "[[concepts/actionable-possibilities]]"
  - "[[concepts/pan-agi]]"
related_entities: []
sources:
  - "[[sources/critiques-of-world-models]]"
evergreen: false
---

# Hypothetical Thinking

## Definition

The psychological and cognitive ability to mentally simulate multiple possible outcomes of actions and plans to chart optimal paths forward. In the context of AI systems, hypothetical thinking refers to using an internal world model to generate and evaluate counterfactual scenarios, enabling goal-oriented reasoning and decision-making in complex, multi-step environments without requiring actual interaction or execution.

## Why It Matters

Hypothetical thinking is the fundamental cognitive mechanism that world models should enable. Rather than reasoning through deterministic optimization algorithms, agents reason by simulating possible futures. This capability enables transfer learning (a skill learned in one domain transfers to novel environments by mechanistic commonality), exploration, and planning under uncertainty. The concept bridges psychology and machine learning, grounding AI world models in human cognitive science.

## Variants / Approaches

- **Mental simulation of action outcomes**: Envisioning consequences of candidate actions before executing them
- **Counterfactual reasoning**: Simulating "what-if" scenarios to understand causal relationships
- **Multi-path exploration**: Simulating multiple candidate plans to select the best expected outcome
- **Goal-conditioned planning**: Simulating backward from desired goal states to identify viable action sequences
- **Uncertainty reasoning**: Simulating distributions over possible outcomes, not point predictions

## Evidence

- Humans reason by simulating multiple possible outcomes, especially in high-stakes decisions [[sources/critiques-of-world-models]]
- The psychology literature on hypothetical thinking shows it enables transfer to novel tasks by leveraging mechanistic commonalities [[sources/critiques-of-world-models]]
- Dune's Kwisatz Haderach visualizes superhuman hypothetical thinking: simulating all possible futures to chart optimal plans [[sources/critiques-of-world-models]]
- World models that enable hypothetical thinking differ from mere next-token predictors; they support extended reasoning [[sources/critiques-of-world-models]]

## Open Questions

- How can AI systems efficiently simulate large numbers of hypothetical scenarios without combinatorial explosion?
- What representational formats best support hypothetical reasoning across physical, social, and abstract domains?
- How does hypothetical thinking relate to interpretability and explainability of AI reasoning?
- Can hypothetical thinking be learned end-to-end, or does it require explicit architectural support?

## Contradictions

<!-- Leave blank if none exist. -->
