---
type: log
format: "## [YYYY-MM-DD HH:MM] <operation> | <short-title>"
---

# Wiki Log

_Chronological, append-only. Do not reorder or edit past entries._
_Grep all entries: `grep "^## \[" wiki/log.md`_

---

## Format Reference

```
## [2026-04-19 14:30] ingest | Karpathy LLM Wiki Gist

- Pages created: [[sources/karpathy-llm-wiki]], [[entities/AndrejKarpathy]], [[concepts/compile-once-maintain-forever]]
- Pages updated: [[wiki/index]]
- Contradictions found: none
- Notes: First ingest. Source language: English.
```

```
## [2026-04-19 15:00] query | Unterschied Wiki vs RAG

- Query: "Was ist der Unterschied zwischen LLM-Wiki und RAG?"
- Pages consulted: [[concepts/compile-once-maintain-forever]], [[sources/karpathy-llm-wiki]]
- Filed as: none (User declined)
```

```
## [2026-04-19 16:00] lint | Weekly health check

- Orphans: [[entities/SomeName]] (no inbound links)
- Stubs: [[concepts/foo]] (32 words)
- Missing Concepts: "attention mechanism" (mentioned in 4 pages, no own page)
- Contradictions: [[sources/paper-a]] ↔ [[sources/paper-b]] on claim X
- Broken Links: none
- Index-Drift: none
- Report: [[lint-reports/2026-04-19]]
```

---

_Workspace initialized. First entry will appear after `/bootstrap` and first `/ingest`._

---

## [2026-06-03 14:42] ingest | Neuralink and the Brain's Magical Future

- Pages created:
  - [[sources/neuralink-and-the-brains-magical-future]]
  - [[entities/Elon-Musk]]
  - [[entities/Tim-Urban]]
  - [[entities/Neuralink]]
  - [[entities/Paul-Merolla]]
  - [[concepts/brain-machine-interface]]
  - [[concepts/neuron]]
  - [[concepts/action-potential]]
  - [[concepts/synapse]]
  - [[concepts/neurotransmitter]]
  - [[concepts/myelin-sheath]]
  - [[concepts/neural-network]]
  - [[concepts/neuroplasticity]]
  - [[concepts/cortex]]
  - [[concepts/gray-matter]]
  - [[concepts/white-matter]]
  - [[concepts/central-nervous-system]]
  - [[concepts/peripheral-nervous-system]]
  - [[concepts/sensory-neuron]]
  - [[concepts/motor-neuron]]
  - [[concepts/interneuron]]
- Pages updated: [[wiki/index]]
- Contradictions found: none
- Notes: Technical focus prioritized. Source language: English. Article explores brain evolution, neuroscience fundamentals, and Neuralink's brain-machine interface mission.

---

## [2026-06-03 15:15] ingest | Learning How to Learn

- Pages created:
  - [[sources/learning-how-to-learn]]
  - [[entities/Barbara-Oakley]]
  - [[concepts/focused-mode]]
  - [[concepts/diffuse-mode]]
  - [[concepts/chunking]]
  - [[concepts/active-recall]]
  - [[concepts/spaced-repetition]]
  - [[concepts/pomodoro-technique]]
  - [[concepts/procrastination]]
  - [[concepts/memory-palace]]
  - [[concepts/mnemonics]]
  - [[concepts/sleep-and-learning]]
  - [[concepts/exercise-and-learning]]
  - [[concepts/input-hygiene]]
  - [[concepts/illusion-of-competence]]
- Pages updated: [[wiki/index]]
- Contradictions found: none
- Notes: Focus on practical learning techniques with comprehensive coverage of neuroscience, brain mechanisms, and memory strategies. Source language: English. Material covers 8 core learning techniques from Coursera course.

---

## [2026-06-03 15:28] query | How neuroplasticity plays crucial role in memory and learning

- Pages consulted: [[concepts/neuroplasticity]], [[concepts/neural-network]], [[concepts/active-recall]], [[concepts/spaced-repetition]], [[concepts/chunking]], [[concepts/sleep-and-learning]]
- Filed as: [[overviews/neuroplasticity-and-learning]]
- Query: "How neuroplasticity plays crucial role in our memory functions and overall learning as well?"

---

## [2026-06-03 15:28] file | neuroplasticity-and-learning

- Filed as: [[overviews/neuroplasticity-and-learning]]
- Type: Overview
- Source query: "How neuroplasticity plays crucial role in our memory functions and overall learning as well?"
- Citations preserved: [[concepts/neuroplasticity]], [[concepts/neural-network]], [[concepts/active-recall]], [[concepts/spaced-repetition]], [[concepts/chunking]], [[concepts/sleep-and-learning]]
- Notes: Synthesis integrating neuroscience (from Neuralink source) with practical learning techniques (from Learning How to Learn source). Demonstrates cross-source insight discovery.
