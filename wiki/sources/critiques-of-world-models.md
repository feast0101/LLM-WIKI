---
type: source
title: Critiques of World Models
source_url: https://arxiv.org/abs/2507.05169v3
source_path: raw/papers/world_model_critiques.pdf
fetched_at: 2026-06-07
ingested_at: 2026-06-07
authors:
  - "[[Eric-Xing]]"
  - "[[Mingkai-Deng]]"
  - "[[Jinyu-Hou]]"
  - "[[Zhiting-Hu]]"
tags:
  - world-models
  - reasoning
  - generative-models
  - agent-architecture
  - hypothetical-thinking
key_entities:
  - "[[Institute-of-Foundation-Models]]"
  - "[[Mohamed-bin-Zayed-University-of-Artificial-Intelligence]]"
  - "[[Carnegie-Mellon-University]]"
  - "[[UC-San-Diego]]"
key_concepts:
  - "[[concepts/hypothetical-thinking]]"
  - "[[concepts/actionable-possibilities]]"
  - "[[concepts/pan-agi]]"
  - "[[concepts/hierarchical-representations]]"
  - "[[concepts/generative-learning]]"
  - "[[concepts/world-models]]"
  - "[[concepts/simulative-reasoning]]"
---

# Critiques of World Models

## Summary

This essay provides empirical and technical critiques of contemporary world modeling approaches and proposes a unified framework grounded in the psychological concept of "hypothetical thinking." The paper draws inspiration from Frank Herbert's *Dune*, where the protagonist simulates outcomes of all possible plans to chart optimal paths. The authors argue that the primary goal of a world model is to simulate all actionable possibilities of the real world for purposeful reasoning and acting.

The authors critique several schools of thought on world modeling (representation choices, architectures, objectives, and usage patterns) and propose an alternative architecture: **PAN (Physical, Agentic, and Nested)** world models. Key design principles include: (1) data from all modalities of experience; (2) mixed continuous and discrete representations; (3) hierarchical generative modeling with an enhanced LLM backbone and generative latent predictive architecture; (4) generative loss grounded in observation data; and (5) using the world model to simulate experience for training agents via reinforcement learning.

The paper positions world models as crucial substrates for agent decision-making, enabling zero-shot transfer to novel tasks by leveraging shared mechanistic commonalities across scenarios. A world model f operates on an internal representation (belief state) derived from sensory inputs, predicting next states given proposed actions—enabling multi-step planning through simulation rather than deterministic optimization.

## Key Claims

- A world model is fundamentally a generative model simulating possibilities across diverse scenarios (physical, mental, social, evolutionary) [[sources/critiques-of-world-models]]
- Hypothetical thinking—the ability to mentally simulate multiple outcomes—is the core cognitive mechanism that world models should enable [[sources/critiques-of-world-models]]
- Optimal agent decision-making requires two components: a policy (selecting actions given current state) and a universe model (predicting next state given action and state) [[sources/critiques-of-world-models]]
- Agents need world models as surrogates of the environment for reasoning and planning when perfect real-time access to true world state is unavailable [[sources/critiques-of-world-models]]
- World models enable transfer of knowledge to solving novel tasks by leveraging mechanistic commonalities across scenarios [[sources/critiques-of-world-models]]
- Five key desiderata for building a world model: training data preparation, general representation space, effective reasoning architecture, proper training objective, and integration into decision-making [[sources/critiques-of-world-models]]
- PAN (Physical, Agentic, Nested) architecture addresses limitations of existing approaches through hierarchical, multi-level, mixed continuous/discrete representations [[sources/critiques-of-world-models]]
- Generative learning frameworks with self-supervised objectives are necessary for scaling world models [[sources/critiques-of-world-models]]

## Notable Quotes

> "What would you do if you could perfectly simulate the next world – every possible future in the environment that we reside?"

## Open Questions

- How can hierarchical world models balance fidelity at multiple levels of abstraction without excessive computational overhead?
- What loss functions best ground generative world models in observation data across physical, social, and abstract domains?
- How does the PAN architecture handle the discrete-continuous boundary in domains like social interaction or scientific discovery?
- Can a single unified world model architecture support physical manipulation, software navigation, social reasoning, and scientific hypothesis testing simultaneously?

## Contradictions

- [[sources/critiques-of-world-models]] emphasizes hierarchical, nested representations as essential for general-purpose world models, while [[sources/agentic-world-modeling]] abstracts away from modality and representation, focusing instead on capability levels and governing-law regimes. The relationship between representational hierarchy and capability hierarchy remains underspecified.

## Related Pages

- [[entities/Institute-of-Foundation-Models]]
- [[entities/Mohamed-bin-Zayed-University-of-Artificial-Intelligence]]
- [[entities/Carnegie-Mellon-University]]
- [[entities/UC-San-Diego]]
- [[concepts/hypothetical-thinking]]
- [[concepts/actionable-possibilities]]
- [[concepts/pan-agi]]
- [[concepts/hierarchical-representations]]
- [[concepts/generative-learning]]
- [[concepts/world-models]]
- [[concepts/simulative-reasoning]]
