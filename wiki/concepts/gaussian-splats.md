---
type: concept
name: gaussian-splats
related_concepts:
  - renderer
  - 3d-reconstruction
  - neural-rendering
related_entities:
  - "[[entities/World-Labs]]"
sources:
  - "[[sources/a-functional-taxonomy-of-world-models]]"
evergreen: false
---

# Gaussian Splats

## Definition

Gaussian splats (or 3D Gaussian Splatting) is a neural rendering technique that represents 3D scenes as a collection of Gaussian basis functions. Rather than storing explicit geometry (meshes) or volumetric data (voxels), Gaussian splats encode a scene as a set of 3D Gaussians with learnable parameters (position, covariance, opacity, spherical harmonics for color). This representation enables efficient rendering from novel viewpoints while maintaining visual quality.

## Why It Matters

Gaussian splats are significant for world models because they provide a compact, efficient representation for photorealistic view synthesis. They sit at the intersection of visual fidelity (renderer concern) and geometric structure (simulator concern). World Labs' Marble outputs Gaussian splats for visual exploration, demonstrating how a single representation can serve both human-facing visualization and machine-learning needs.

## Variants / Approaches

- **View-dependent rendering** — Spherical harmonics for realistic material appearance
- **Adaptive density control** — Automated refinement of Gaussian placement for efficiency
- **Real-time rasterization** — GPU-optimized rendering enabling interactive exploration

## Evidence

- [[sources/a-functional-taxonomy-of-world-models]] — Notes that Marble outputs Gaussian splats for visual exploration alongside collision meshes for physics simulation; positions this dual output as dissolving the boundary between renderer and simulator.

## Open Questions

- How can Gaussian splats be made fully compatible with physics simulation?
- Can Gaussian splats learn implicit physics from rendering data?
- How do Gaussian splats scale to large, complex scenes?
- What is the trade-off between Gaussian complexity and rendering speed?

## Contradictions

None identified.
