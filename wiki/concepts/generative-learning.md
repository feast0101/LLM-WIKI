---
type: concept
name: Generative Learning
related_concepts:
  - "[[concepts/world-models]]"
  - "[[concepts/pan-agi]]"
  - "[[concepts/hierarchical-representations]]"
  - "[[concepts/simulative-reasoning]]"
related_entities: []
sources:
  - "[[sources/critiques-of-world-models]]"
evergreen: false
---

# Generative Learning

## Definition

A training framework for world models where the primary objective is to generate (simulate) plausible future states, observations, or trajectories conditioned on current state and action. Generative learning contrasts with discriminative learning (distinguishing classes) or contrastive learning (comparing examples). In world modeling, generative frameworks typically employ self-supervised objectives grounded in observation data—the model learns by predicting actual future observations from current ones.

## Why It Matters

Generative learning is fundamental for scaling world models because: (1) it doesn't require explicit labels (unsupervised/self-supervised), (2) it provides rich training signals from high-dimensional observation data, (3) it naturally supports multi-step rollout training, and (4) it aligns with the functional goal of world models (simulating futures). The Critiques of World Models paper identifies generative loss grounded in observation data as a key design principle for PAN AGI.

## Variants / Approaches

- **Next-step prediction loss**: Train to predict next observation/state given current and action
- **Multi-step rollout loss**: Compose predictions into multi-step trajectories, optimizing end-to-end
- **Variational objectives**: Learn distributions over futures (VAE-style) to capture stochasticity
- **Diffusion-based generation**: Use diffusion models to iteratively refine predictions
- **Adversarial learning**: Use discriminators to ensure generated trajectories are realistic
- **Self-supervised losses**: Learn from unlabeled interaction data without explicit supervision

## Evidence

- Generative frameworks are essential for scaling world models to high-dimensional observation spaces [[sources/critiques-of-world-models]]
- Self-supervised objectives enable learning from unlabeled data, critical for large-scale learning [[sources/critiques-of-world-models]]
- Observation-grounded loss (matching actual future observations) is a key principle in PAN AGI [[sources/critiques-of-world-models]]
- Large-scale generative models (diffusion, autoregressive) have enabled advances in video generation and world modeling [[sources/critiques-of-world-models]]

## Open Questions

- What loss functions best balance sample efficiency and computational cost?
- How should generative learning handle stochasticity and multi-modality in future predictions?
- Can generative learning alone ensure that simulated futures support good agent planning?
- How do generative objectives interact with hierarchical representations and decision-centric evaluation?
- What role do perceptual loss functions (e.g., LPIPS, StyleGAN loss) play in generative world models?

## Contradictions

<!-- Leave blank if none exist. -->
