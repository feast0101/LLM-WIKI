---
type: source
title: Agentic World Modeling - Foundations, Capabilities, Laws, and Beyond
source_url: https://arxiv.org/abs/2604.22748v1
source_path: raw/papers/agentic_world_modeling.pdf
fetched_at: 2026-06-07
ingested_at: 2026-06-07
authors:
  - "[[Meng-Chu]]"
  - "[[Xuan-Billy-Zhang]]"
  - "[[Kevin-Qinghong-Lin]]"
  - "[[Lingdong-Kong]]"
  - "[[Jize-Zhang]]"
  - "[[Teng-Tu]]"
  - "[[Weijian-Ma]]"
  - "[[Ziqi-Huang]]"
  - "[[Senqiao-Yang]]"
  - "[[Wei-Huang]]"
  - "[[Yeying-Jin]]"
  - "[[Zhefan-Rao]]"
  - "[[Jinhui-Ye]]"
  - "[[Xinyu-Lin]]"
  - "[[Xichen-Zhang]]"
  - "[[Qisheng-Hu]]"
  - "[[Shuai-Yang]]"
  - "[[Leyang-Shen]]"
  - "[[Wei-Chow]]"
  - "[[Yifei-Dong]]"
  - "[[Fengyi-Wu]]"
  - "[[Quanyu-Long]]"
  - "[[Bin-Xia]]"
  - "[[Shaozuo-Yu]]"
  - "[[Mingkang-Zhu]]"
  - "[[Wenhu-Zhang]]"
  - "[[Jiehui-Huang]]"
  - "[[Haokun-Gui]]"
  - "[[Haoxuan-Che]]"
  - "[[Long-Chen]]"
  - "[[Qifeng-Chen]]"
  - "[[Wenxuan-Zhang]]"
  - "[[Wenya-Wang]]"
  - "[[Xiaojuan-Qi]]"
  - "[[Yang-Deng]]"
  - "[[Yanwei-Li]]"
  - "[[Mike-Zheng-Shou]]"
  - "[[Zhi-Qi-Cheng]]"
  - "[[See-Kiong-Ng]]"
  - "[[Ziwei-Liu]]"
  - "[[Philip-Torr]]"
  - "[[Jiaya-Jia]]"
tags:
  - world-models
  - agentic-ai
  - taxonomy
  - prediction
  - simulation
  - agent-learning
key_entities:
  - "[[HKUST]]"
  - "[[National-University-of-Singapore]]"
  - "[[University-of-Oxford]]"
  - "[[Nanyang-Technological-University]]"
key_concepts:
  - "[[concepts/predictor]]"
  - "[[concepts/simulator]]"
  - "[[concepts/evolver]]"
  - "[[concepts/physical-law]]"
  - "[[concepts/digital-law]]"
  - "[[concepts/social-law]]"
  - "[[concepts/scientific-law]]"
  - "[[concepts/levels-laws-taxonomy]]"
  - "[[concepts/world-models]]"
---

# Agentic World Modeling - Foundations, Capabilities, Laws, and Beyond

## Summary

This comprehensive survey (400+ cited works) introduces a "levels × laws" taxonomy for understanding world modeling in agentic AI systems. The paper addresses fundamental conceptual fragmentation across communities (vision, RL, robotics, web agents, social simulation, scientific discovery) where the term "world model" carries different meanings.

The authors organize world models along two axes: (1) **Three capability levels**: L1 Predictor (learns one-step local transitions), L2 Simulator (composes multi-step, action-conditioned rollouts respecting domain laws), and L3 Evolver (autonomously revises its model when predictions fail against new evidence); and (2) **Four governing-law regimes**: Physical (objects, forces, navigation), Digital (program semantics, GUIs), Social (beliefs, norms, coordination), and Scientific (latent mechanisms, causal structure).

The paper synthesizes over 100 representative systems spanning model-based reinforcement learning, video generation, web/GUI agents, multi-agent social simulation, and AI-driven scientific discovery. It proposes decision-centric evaluation principles, a minimal reproducible evaluation package, and architectural guidance. The roadmap connects previously isolated communities and charts a path from passive next-step prediction toward world models that can simulate and ultimately reshape environments in which agents operate.

Key distinction from prior taxonomies: rather than organizing by modality (text, vision, 3D) or application domain (autonomous driving, robotics), this framework cuts across modalities with a capability-centric lens, asking what progressively harder abilities world models must exhibit—local prediction, constraint-valid simulation, and evidence-driven self-correction.

## Key Claims

- World models serve agentic decision-making by learning state-transition dynamics: given a state and action, predict the resulting next state [[sources/agentic-world-modeling]]
- Capability levels are not mutually exclusive model classes but stages of progression; the same system may invoke different levels depending on task demand [[sources/agentic-world-modeling]]
- L1 Predictor focuses on one-step, local transition operators; insufficient for multi-step planning [[sources/agentic-world-modeling]]
- L2 Simulator composes transitions into multi-step, action-conditioned rollouts that respect domain laws; enables look-ahead planning [[sources/agentic-world-modeling]]
- L3 Evolver autonomously revises its model when predictions fail against new evidence; enables learning from out-of-distribution scenarios [[sources/agentic-world-modeling]]
- Four governing-law regimes (physical, digital, social, scientific) determine what constraints a world model must satisfy and where it is most likely to fail [[sources/agentic-world-modeling]]
- The intensifying debate over whether large-scale generative models are merely plausible generators or genuine world simulators requires precision via capability-based taxonomy [[sources/agentic-world-modeling]]
- Decision-centric evaluation differs fundamentally from visual-fidelity evaluation; a renderer may output visually correct pixels yet fail to support simulation or robotics [[sources/agentic-world-modeling]]
- Existing modality-centric and domain-centric taxonomies fail to capture the capability progression cutting across modalities (e.g., latent-space imagination in MBRL vs. visual generation) [[sources/agentic-world-modeling]]

## Notable Quotes

> "As AI systems move from generating text to accomplishing goals through sustained interaction, the ability to model environment dynamics becomes a central bottleneck."

## Open Questions

- What are the precise boundary conditions between L2 (Simulator) and L3 (Evolver) across different regimes?
- How can reproducible evaluation be standardized across disparate domains (embodied manipulation, web navigation, social simulation, scientific discovery)?
- What architectural patterns generalize across the L1–L3 spectrum and across the four law regimes?
- How do hybrid systems (e.g., simulators that occasionally invoke evidence-driven revision) fit within the levels hierarchy?
- What are the failure modes unique to L3 Evolvers when dealing with distributional shift or adversarial interventions?

## Related Pages

- [[entities/HKUST]]
- [[entities/National-University-of-Singapore]]
- [[entities/University-of-Oxford]]
- [[entities/Nanyang-Technological-University]]
- [[concepts/predictor]]
- [[concepts/simulator]]
- [[concepts/evolver]]
- [[concepts/physical-law]]
- [[concepts/digital-law]]
- [[concepts/social-law]]
- [[concepts/scientific-law]]
- [[concepts/levels-laws-taxonomy]]
- [[concepts/world-models]]
