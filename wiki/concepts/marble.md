---
type: concept
name: marble
related_concepts:
  - world-models
  - simulator
  - renderer
  - gaussian-splats
  - physics-engine
related_entities:
  - "[[entities/World-Labs]]"
sources:
  - "[[sources/a-functional-taxonomy-of-world-models]]"
evergreen: false
---

# Marble

## Definition

Marble is World Labs' foundational world model system. It takes multimodal prompts (text, image, video, or spatial sketch) as input and generates explorable 3D environments. Marble outputs both Gaussian splats for visual exploration and collision meshes that physics engines can operate on, effectively combining renderer and simulator capabilities in a single model.

## Why It Matters

Marble represents a concrete instantiation of the theoretical unified world model—it demonstrates the feasibility of a single foundation model that can render photorealistic views and produce physically accurate structure. It is World Labs' first move into unifying the rendering-simulation boundary, and the company describes Marble as "only the first chapter of a much longer arc" in dissolving boundaries between rendering, simulation, and planning.

## Variants / Approaches

- **Multimodal conditioning** — Accepts diverse input types (text, image, video, sketches)
- **Dual output modality** — Generates both visual and physics-ready representations
- **Interactive exploration** — Generates 3D environments that humans can explore

## Evidence

- [[sources/a-functional-taxonomy-of-world-models]] — Presented as World Labs' primary product and example of the unified world model approach; outputs Gaussian splats and collision meshes from a single model; described as dissolving the boundary between renderer and simulator.

## Open Questions

- What is the trade-off between visual beauty and physical accuracy in Marble?
- How can Marble be extended to handle more complex multi-physics scenarios?
- How will Marble integrate with planning systems for embodied AI?
- What training data will be needed to scale Marble to greater environmental complexity?

## Contradictions

None identified.
