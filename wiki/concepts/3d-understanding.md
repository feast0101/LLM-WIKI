---
type: concept
name: 3d-understanding
related_concepts:
  - spatial-intelligence
  - world-models
  - renderer
  - simulator
related_entities:
  - "[[entities/World-Labs]]"
sources:
  - "[[sources/from-words-to-worlds-spatial-intelligence]]"
  - "[[sources/a-functional-taxonomy-of-world-models]]"
evergreen: false
---

# 3D Understanding

## Definition

3D understanding is the ability of an AI system to perceive, represent, and reason about three-dimensional structure, geometry, and spatial relationships in the world. This includes understanding object shape, size, pose, material properties, and how objects relate to each other in 3D space. 3D understanding is distinct from 2D vision (which processes flat images) and enables reasoning about occlusions, viewpoint changes, and three-dimensional interactions.

## Why It Matters

3D understanding is a foundational component of spatial intelligence. While 2D vision can recognize objects in images, 3D understanding enables systems to reason about how objects appear from different angles, how they move through space, and how they interact physically. This is essential for robotics, autonomous vehicles, architectural visualization, and scientific discovery. Unlike language models which are grounded only in text, AI systems with genuine 3D understanding are grounded in the physical structure of the world.

## Variants / Approaches

- **Explicit 3D representation** — Stores geometry as meshes, point clouds, or voxels
- **Implicit 3D representation** — Learns latent 3D structure without explicit geometry
- **Differentiable 3D rendering** — Enables learning 3D structure from 2D images
- **Neural 3D fields** — Coordinate-based networks (NeRF, Gaussian splats) that encode 3D scenes

## Evidence

- [[sources/from-words-to-worlds-spatial-intelligence]] — Positions 3D understanding as essential for spatial intelligence; contrasts with language models' lack of spatial grounding.
- [[sources/a-functional-taxonomy-of-world-models]] — Discusses 3D data scarcity; notes that 3D geometry with explicit material and physical annotations is orders of magnitude scarcer than internet video.

## Open Questions

- How can AI systems learn robust 3D understanding from sparse training data?
- What is the optimal representation for 3D scenes in learning systems?
- How can 3D understanding scale to real-world environments with unlimited complexity?
- How will 3D understanding integrate with language understanding for embodied reasoning?

## Contradictions

None identified.
