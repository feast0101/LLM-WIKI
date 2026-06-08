---
type: concept
name: renderer
related_concepts:
  - world-models
  - simulator
  - planner
  - gaussian-splats
  - visual-fidelity
related_entities:
  - "[[entities/Google]]"
sources:
  - "[[sources/a-functional-taxonomy-of-world-models]]"
evergreen: false
---

# Renderer

## Definition

A renderer is a type of world model that outputs observations in the form of pixels meant for human eyes. The quality metric is visual fidelity. Renderers produce photorealistic or visually plausible views but do not necessarily carry explicit understanding of three-dimensional structure or physical accuracy. They generate what a viewer would see, not what is structurally or physically true.

## Why It Matters

Renderers are the most commercially mature category of world models. They power consumer applications like text-to-video generation and interactive visual systems. They excel at creating visually compelling content for storytelling, media, and entertainment. However, their limitation is that visual plausibility does not equal structural or physical accuracy—buildings may look flawless from above but fall apart under scrutiny from other angles or when subject to physics simulation.

## Variants / Approaches

- **Passive renderers** — Generate static images or video conditioned on prompts or text
- **Interactive renderers** — Generate frames in real-time conditioned on user input (e.g., allowing viewport navigation)
- **Multimodal renderers** — Accept multiple input modalities (text, image, video, spatial sketches)

## Evidence

- [[sources/a-functional-taxonomy-of-world-models]] — Defines renderer as the first functional category; notes visual models like Google Genie 3 and text-to-video systems; points out ceiling limitation (visual plausibility vs. physical accuracy).

## Open Questions

- How can renderers be made to respect geometric consistency across viewpoints?
- Can renderers be designed to implicitly learn physics without explicit supervision?
- What is the trade-off between visual beauty and structural plausibility?

## Contradictions

None identified.
