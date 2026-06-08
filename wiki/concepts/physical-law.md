---
type: concept
name: Physical Law (Governing-Law Regime)
related_concepts:
  - "[[concepts/levels-laws-taxonomy]]"
  - "[[concepts/world-models]]"
  - "[[concepts/digital-law]]"
  - "[[concepts/social-law]]"
  - "[[concepts/scientific-law]]"
  - "[[concepts/physics-engine]]"
  - "[[concepts/embodied-ai]]"
  - "[[concepts/sim-to-real]]"
related_entities: []
sources:
  - "[[sources/agentic-world-modeling]]"
evergreen: false
---

# Physical Law (Governing-Law Regime)

## Definition

One of four governing-law regimes in the agentic world modeling taxonomy. The Physical Law regime encompasses systems where world models must respect Newton's laws, conservation principles, and the mechanics of object interactions, spatial reasoning, and physical dynamics. Domains include robotic manipulation, autonomous navigation, autonomous driving, egocentric video prediction, action-conditioned video modeling, and 3D world modeling.

## Why It Matters

Physical-law regimes are among the most extensively studied in world modeling research, with decades of work in robotics, physics engines, and learned dynamics models. However, physical plausibility is necessary but not sufficient: a model that generates visually correct pixels may violate conservation of momentum or geometric consistency. The governing-law lens clarifies what constraints a world model must satisfy in physical domains and where it is most likely to fail.

## Variants / Approaches

- **Physics-engine-based modeling**: Explicit simulation of rigid bodies, deformable objects, fluids, cloth
- **Learned dynamics models**: Neural networks predicting state transitions while respecting physical laws
- **Hybrid symbolic-neural approaches**: Combine symbolic physics with learned components for efficiency and accuracy
- **Video prediction with physics grounding**: Generate next frames while maintaining geometric and physical consistency
- **3D world modeling**: Represent and simulate 3D scenes with spatially consistent geometry and physics

## Evidence

- Robotic manipulation and navigation systems rely on physical-law simulators [[sources/agentic-world-modeling]]
- Autonomous driving requires world models respecting vehicle dynamics and collision physics [[sources/agentic-world-modeling]]
- Model-based RL in continuous control tasks (DayDreamer, MuZero) instantiate physical-law simulators [[sources/agentic-world-modeling]]
- World Labs' work on 3D world modeling emphasizes physical accuracy over visual appearance [[sources/a-functional-taxonomy-of-world-models]]

## Open Questions

- How can learned dynamics models efficiently enforce conservation laws without explicit physics engines?
- What is the optimal trade-off between physical accuracy and computational efficiency in multi-step planning?
- How does the sim-to-real gap arise in physical-law regimes, and what training strategies minimize it?
- Can a single world model architecture handle diverse physical scenarios (soft bodies, fluids, articulated objects)?
- How do physical-law simulators handle model uncertainty, object ambiguity, and partial observability?

## Contradictions

<!-- Leave blank if none exist. -->
