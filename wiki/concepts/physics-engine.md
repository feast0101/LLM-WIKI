---
type: concept
name: physics-engine
related_concepts:
  - simulator
  - world-models
  - collision-detection
  - dynamics-simulation
related_entities:
  - "[[entities/World-Labs]]"
  - "[[entities/NVIDIA]]"
sources:
  - "[[sources/a-functional-taxonomy-of-world-models]]"
evergreen: false
---

# Physics Engine

## Definition

A physics engine is a computational system that simulates physical interactions in a digital environment, enforcing the laws of physics (Newton's laws of motion, gravity, collisions, friction, etc.). Physics engines are a core component of simulators, enabling them to produce dynamically accurate behavior. They can operate on collision meshes and other geometric representations to determine how objects move, collide, deform, and interact.

## Why It Matters

Physics engines are critical infrastructure for world models, particularly simulators. They enable AI-generated environments to behave realistically and predictably, which is essential for training embodied agents (robots, autonomous vehicles) in simulation before deploying them in the real world. Physics engines bridge the gap between visual representation (what something looks like) and physical behavior (how it actually moves and interacts).

## Variants / Approaches

- **Rigid body dynamics** — Simulates solid objects with no deformation
- **Deformable object simulation** — Handles cloth, fluids, soft bodies
- **Multi-physics simulation** — Combines rigid bodies, deformables, fluids, and cloth
- **Analytical physics engines** — Hand-coded physics for efficiency
- **Learning-based physics models** — Neural networks trained to predict physical dynamics

## Evidence

- [[sources/a-functional-taxonomy-of-world-models]] — Notes physics engines as component of simulators; mentions multi-physics simulation at scale (rigid bodies, deformable objects, fluids, cloth) as open problem; discusses cost differential between single-domain and multi-physics simulation.

## Open Questions

- How can physics engines be made efficient at interactive scale?
- How can learning-based physics models ensure physical validity while maintaining accuracy?
- What is the optimal balance between analytical and learned physics?
- How can sim-to-real transfer account for physics simulation inaccuracies?

## Contradictions

None identified.
