---
type: concept
name: Digital Law (Governing-Law Regime)
related_concepts:
  - "[[concepts/levels-laws-taxonomy]]"
  - "[[concepts/world-models]]"
  - "[[concepts/physical-law]]"
  - "[[concepts/social-law]]"
  - "[[concepts/scientific-law]]"
  - "[[concepts/world-models]]"
related_entities: []
sources:
  - "[[sources/agentic-world-modeling]]"
evergreen: false
---

# Digital Law (Governing-Law Regime)

## Definition

One of four governing-law regimes in the agentic world modeling taxonomy. The Digital Law regime encompasses systems where world models must respect program semantics, computational determinism, code logic, and digital user interface behavior. Domains include web navigation, software tool use, GUI environment interaction, and code execution.

## Why It Matters

Digital-law world models enable agents to reason about software systems and computational environments. Unlike the physical world where violations of Newton's laws are obvious, digital environments can mask semantic violations (a model predicts a visually plausible GUI state that violates actual program logic). The governing-law lens clarifies that digital environments have their own set of constraints—program semantics are as absolute as physics in determining what state transitions are valid.

## Variants / Approaches

- **Semantic parsing and understanding**: Parse code and UI specifications to understand what transitions are valid
- **Deterministic simulation**: Execute code symbolically or via interpretation to predict exact state transitions
- **Learned program semantics**: Train models to predict next UI states given current UI and actions
- **Code-grounded reasoning**: Embed understanding of program structure to constrain predictions
- **Hybrid symbolic-neural**: Combine symbolic execution with neural learning for efficiency

## Evidence

- Web agents (WebDreamer) use digital-law simulators to predict how websites respond to interactions [[sources/agentic-world-modeling]]
- Software tool-use agents (SWE-agent) require understanding of program semantics and CLI behavior [[sources/agentic-world-modeling]]
- GUI navigation systems must respect application logic and state machines [[sources/agentic-world-modeling]]
- Code generation and execution agents (CodeIt, CodeWM) reason about digital-law constraints [[sources/agentic-world-modeling]]

## Open Questions

- How can world models efficiently learn and represent program semantics at scale?
- What is the optimal balance between symbolic execution and learned digital-law models?
- How do digital-law simulators handle non-determinism, randomness, and asynchronous behavior?
- Can a single architecture support web navigation, CLI interaction, and code execution?
- How are digital-law world models evaluated: by UI fidelity, semantic correctness, or task success?

## Contradictions

<!-- Leave blank if none exist. -->
