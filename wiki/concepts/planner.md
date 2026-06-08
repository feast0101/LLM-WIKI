---
type: concept
name: planner
related_concepts:
  - world-models
  - renderer
  - simulator
  - embodied-ai
  - action-models
related_entities:
  - "[[entities/World-Labs]]"
sources:
  - "[[sources/a-functional-taxonomy-of-world-models]]"
evergreen: false
---

# Planner

## Definition

A planner is a type of world model that outputs actions. Given an observation and a goal, a planner predicts what an agent should do next. Planners close the perception-action loop by consuming observations and producing action sequences. This is, in many ways, the inverse of a renderer, which consumes actions and produces observations.

## Why It Matters

Planners are essential for embodied agents—robots, autonomous vehicles, and other systems that must act in unstructured environments. Planners represent the most nascent category of world models but also the most intriguing for practical AI applications. Success in planning means robots that can work reliably in kitchens, warehouses, and operating rooms. The entire robotics industry is racing to be the one that solves robust, general-purpose planning.

## Variants / Approaches

- **Vision-Language-Action models** — Integrate visual perception and language understanding to predict actions
- **Model-based planners** — Use explicit world models to predict action consequences
- **World Action Models** — Newer wave combining world modeling with action prediction

## Evidence

- [[sources/a-functional-taxonomy-of-world-models]] — Defines planner as the third functional category; notes that planners are nascent and closely connected to robotic learning; acknowledges impressive demos but candid assessment that most are confined to constrained lab settings; highlights gap between compelling demo reels and real-world deployment reliability.

## Open Questions

- How can planning systems handle the complexity, variability, and duration of real-world tasks?
- What training data is needed for general-purpose embodied planning?
- How can sim-to-real transfer be improved for robot control?
- How will visual planning integrate with language understanding?

## Contradictions

None identified.
