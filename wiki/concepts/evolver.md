---
type: concept
name: Evolver (L3 Capability Level)
related_concepts:
  - "[[concepts/predictor]]"
  - "[[concepts/simulator]]"
  - "[[concepts/levels-laws-taxonomy]]"
  - "[[concepts/world-models]]"
  - "[[concepts/physical-law]]"
  - "[[concepts/digital-law]]"
  - "[[concepts/social-law]]"
  - "[[concepts/scientific-law]]"
related_entities: []
sources:
  - "[[sources/agentic-world-modeling]]"
evergreen: false
---

# Evolver (L3 Capability Level)

## Definition

The third and highest capability level in agentic world modeling. An L3 Evolver autonomously revises its own model when predictions fail against new evidence, enabling learning from out-of-distribution scenarios and distributional shifts. It goes beyond multi-step simulation (L2) to incorporate persistent, evidence-driven model correction during deployment.

## Why It Matters

L3 Evolvers address a critical limitation of static simulators: real-world environments change, and agents encounter scenarios not well-represented in training data. An Evolver can adapt its world model online, using prediction errors and mismatch signals to update its beliefs about how the environment works. This capability is essential for long-horizon agentic tasks and robust deployment in open-ended worlds.

## Variants / Approaches

- **Online model adaptation**: Continuously refine world model parameters or add new modes during deployment based on prediction errors
- **Uncertainty-aware revision**: Use epistemic uncertainty to identify when a model should be updated
- **Evidence-driven refinement**: Update model structure or parameters when encountering contradictions with observed dynamics
- **Meta-learning approaches**: Learn how to learn new world models from small amounts of evidence
- **Hybrid discrete-continuous updating**: Revise both continuous parameters and discrete structural choices (e.g., adding new object types or constraints)

## Evidence

- AI for science systems (A-Lab, AI Scientist, BioLab, OriGene) instantiate L3 capabilities, using hypothesis-driven experimentation to refine mechanistic models [[sources/agentic-world-modeling]]
- The formal distinction between L2 and L3 hinges on whether a system can update its model based on failed predictions [[sources/agentic-world-modeling]]
- Model-based RL agents that use experience replay to adapt transition models approach L3 capabilities, though not all achieve autonomous revision [[sources/agentic-world-modeling]]
- Multi-agent social simulation systems that learn to model other agents' changing behaviors exhibit L3-like adaptation [[sources/agentic-world-modeling]]

## Open Questions

- What mechanisms best support stable, efficient online adaptation without catastrophic forgetting?
- How does L3 capability vary across governing-law regimes (physical vs. social vs. scientific)?
- What are the failure modes unique to L3 Evolvers when dealing with adversarial interventions or deceptive feedback?
- How can evolvers balance exploration (testing new hypotheses about the world) with exploitation (using the current model for planning)?
- What are the data efficiency and computational overhead trade-offs of continuous model revision?

## Contradictions

<!-- Leave blank if none exist. -->
