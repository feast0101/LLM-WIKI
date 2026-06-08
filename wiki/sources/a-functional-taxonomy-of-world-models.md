---
type: source
title: A Functional Taxonomy of World Models
source_url: https://x.com/drfeifei/status/2062247238143996275
source_path: raw/articles/A Functional Taxonomy of World Models.md
fetched_at: 2026-06-04
ingested_at: 2026-06-07
authors:
  - "[[Fei-Fei-Li]]"
  - "World Labs team"
tags:
  - world-models
  - spatial-intelligence
  - AI
  - generative-AI
key_entities:
  - "[[Fei-Fei-Li]]"
  - "[[World-Labs]]"
  - "[[NVIDIA]]"
  - "[[Google]]"
key_concepts:
  - "[[concepts/world-models]]"
  - "[[concepts/renderer]]"
  - "[[concepts/simulator]]"
  - "[[concepts/planner]]"
  - "[[concepts/spatial-intelligence]]"
  - "[[concepts/physics-engine]]"
  - "[[concepts/gaussian-splats]]"
  - "[[concepts/pomdp]]"
---

# A Functional Taxonomy of World Models

## Summary

This essay by Fei-Fei Li and the World Labs team provides a foundational taxonomy of world models, clarifying an overloaded term that means different things across computer vision, robotics, reinforcement learning, and generative AI. The authors argue that "world model" is one of the most important and most confused concepts in modern AI research.

At its core, a world model learns the statistical structure of space and time—how light falls on surfaces, how objects respond to force, and how dynamics unfold under physical laws. The essay traces the term's lineage to Kenneth Craik's 1943 work on mental models and to the partially observable Markov decision process (POMDP) framework from reinforcement learning.

The authors identify three distinct functional categories of world models: (1) **Renderers**, which output pixels for human consumption and prioritize visual fidelity; (2) **Simulators**, which output state—geometrically and physically faithful representations that both humans and AI systems can compute on; and (3) **Planners**, which output actions, deciding what an agent should do given observations and goals.

The essay argues that simulators are the critical linchpin, though least commercially visible. While renderers (text-to-video) are mature and planners (robotic learning) nascent, simulators bridge both: they provide the structural backbone from which visual appearance and action consequences can be derived. World Labs' Marble is presented as their first entry into this space, generating 3D environments from multimodal prompts with both visual (Gaussian splats) and physics-ready (collision meshes) outputs.

The essay concludes that the future lies in dissolving boundaries between these three categories, moving toward unified foundation models that can switch between modalities—rendering, simulating, and planning from a single underlying representation of the world.

## Key Claims

- World models learn the statistical structure of space and time, unlike language models which learn text statistics [[sources/a-functional-taxonomy-of-world-models]]
- The term "world model" is fundamentally overloaded; different fields mean entirely different things [[sources/a-functional-taxonomy-of-world-models]]
- Renderers prioritize visual fidelity over structural accuracy; pixels may look correct but cannot support simulation or robotics [[sources/a-functional-taxonomy-of-world-models]]
- Simulators are the linchpin: they can project understanding into pixels for rendering and into actions for planning [[sources/a-functional-taxonomy-of-world-models]]
- The logical endpoint is a unified world model foundation that renders, simulates, and plans from a single representation [[sources/a-functional-taxonomy-of-world-models]]
- Marble (World Labs) outputs both Gaussian splats and collision meshes, bridging renderer and simulator [[sources/a-functional-taxonomy-of-world-models]]
- Three-dimensional training data is orders of magnitude scarcer than internet video [[sources/a-functional-taxonomy-of-world-models]]
- The sim-to-real gap remains a daunting challenge for practical deployment [[sources/a-functional-taxonomy-of-world-models]]

## Notable Quotes

> "Language gave machines a way to talk about that world. World models are how machines will finally come to understand, imagine, reason and interact with it."

## Open Questions

- What specific architectures will unify rendering, simulation, and planning?
- How can sim-to-real transfer be improved to enable reliable real-world robot deployment?
- What is the optimal balance between visual beauty and physical accuracy in unified world models?
- How will training data scarcity for 3D assets be addressed at scale?

## Related Pages

- [[entities/Fei-Fei-Li]]
- [[entities/World-Labs]]
- [[entities/NVIDIA]]
- [[entities/Google]]
- [[concepts/world-models]]
- [[concepts/renderer]]
- [[concepts/simulator]]
- [[concepts/planner]]
- [[concepts/spatial-intelligence]]
- [[concepts/physics-engine]]
- [[concepts/gaussian-splats]]
- [[concepts/pomdp]]
- [[concepts/marble]]
