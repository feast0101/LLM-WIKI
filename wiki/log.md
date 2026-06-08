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

---

## [2026-06-07 12:00] ingest | World Models: Functional Taxonomy and Spatial Intelligence

- Pages created:
  - [[sources/a-functional-taxonomy-of-world-models]]
  - [[sources/from-words-to-worlds-spatial-intelligence]]
  - [[entities/Fei-Fei-Li]]
  - [[entities/World-Labs]]
  - [[entities/NVIDIA]]
  - [[entities/Google]]
  - [[concepts/world-models]]
  - [[concepts/renderer]]
  - [[concepts/simulator]]
  - [[concepts/planner]]
  - [[concepts/spatial-intelligence]]
  - [[concepts/physics-engine]]
  - [[concepts/gaussian-splats]]
  - [[concepts/pomdp]]
  - [[concepts/marble]]
  - [[concepts/embodied-ai]]
  - [[concepts/3d-understanding]]
- Pages updated: [[wiki/index]]
- Contradictions found: none
- Notes: Two complementary sources on world models and spatial intelligence. First source provides functional taxonomy (renderers, simulators, planners); second establishes spatial intelligence as AI's next frontier. Cross-references between sources captured. Focus: technical foundations of world model design and strategic importance of spatial grounding for AI.

---

## [2026-06-07 14:45] ingest | Agentic World Modeling and Critiques of World Models

- Pages created:
  - [[sources/agentic-world-modeling]]
  - [[sources/critiques-of-world-models]]
  - [[entities/HKUST]]
  - [[entities/National-University-of-Singapore]]
  - [[entities/University-of-Oxford]]
  - [[entities/Nanyang-Technological-University]]
  - [[entities/Institute-of-Foundation-Models]]
  - [[entities/Mohamed-bin-Zayed-University-of-Artificial-Intelligence]]
  - [[entities/Carnegie-Mellon-University]]
  - [[entities/UC-San-Diego]]
  - [[concepts/predictor]]
  - [[concepts/evolver]]
  - [[concepts/levels-laws-taxonomy]]
  - [[concepts/physical-law]]
  - [[concepts/digital-law]]
  - [[concepts/social-law]]
  - [[concepts/scientific-law]]
  - [[concepts/hypothetical-thinking]]
  - [[concepts/actionable-possibilities]]
  - [[concepts/pan-agi]]
  - [[concepts/hierarchical-representations]]
  - [[concepts/generative-learning]]
  - [[concepts/simulative-reasoning]]
- Pages updated: 
  - [[concepts/simulator]] (augmented with L2 Capability Level definition)
  - [[wiki/index]]
- Contradictions found: 
  - [[sources/critiques-of-world-models]] ↔ [[sources/agentic-world-modeling]] on representational hierarchy vs. capability hierarchy (recorded in [[concepts/levels-laws-taxonomy]] and [[concepts/hierarchical-representations]])
  - [[sources/critiques-of-world-models]] ↔ [[sources/agentic-world-modeling]] on modality-specific vs. modality-agnostic organization (complementary rather than contradictory)
- Notes: Two major research papers on world modeling introducing distinct organizational frameworks. Agentic World Modeling (Chu et al., 2026) presents Levels × Laws taxonomy (L1/L2/L3 × 4 regimes) synthesizing 400+ works across embodied AI, generative models, language agents, and AI for science. Critiques of World Models (Xing et al., 2025) provides critical analysis and proposes PAN AGI architecture grounded in hypothetical thinking and hierarchical representations. Papers are largely orthogonal with clear cross-references and complementarity. Simulator concept page updated to reflect both functional definition (Fei-Fei Li) and L2 capability level (Agentic World Modeling). Source language: English.

---

## [2026-06-07 16:30] lint | Complete health check

- Contradictions: 3 pages with non-empty contradictions
  - [[concepts/hierarchical-representations]] (hierarchy framing debate)
  - [[concepts/levels-laws-taxonomy]] (representational vs. capability hierarchies)
  - [[sources/critiques-of-world-models]] (self-reference contradiction)
- Orphans: 9 pages with no inbound links
  - 1 overview: [[overviews/neuroplasticity-and-learning]]
  - 8 entities (universities, researchers): [[entities/Carnegie-Mellon-University]], [[entities/Eric-Xing]], [[entities/Institute-of-Foundation-Models]], [[entities/Mohamed-bin-Zayed-University-of-Artificial-Intelligence]], [[entities/Nanyang-Technological-University]], [[entities/National-University-of-Singapore]], [[entities/UC-San-Diego]], [[entities/University-of-Oxford]]
- Stubs: none
- Missing Concepts: "fei-fei li" (referenced 4 times, should be formalized as [[concepts/fei-fei-li]] or in [[entities/Fei-Fei-Li]])
- Stale Claims: none (all sources ingested within 180 days or marked evergreen)
- Broken Links: 119 instances across 44 unique targets
  - 43 entity links with spacing/capitalization mismatches (e.g., "Fei-Fei Li" vs. [[entities/Fei-Fei-Li]])
  - 36 author names from papers not yet created as entities
  - 40 links with embedded claim text (Obsidian pipe-syntax) in [[overviews/neuroplasticity-and-learning]]
- Index Drift: 1 page missing from index
  - [[entities/Eric-Xing]] not in wiki/index.md
- Report: [[lint-reports/2026-06-07]]
- Notes: 133 total issues. Most broken links are due to spacing/capitalization in entity link targets (fixable via batch renaming) and legitimate references to not-yet-created author entity pages. Link syntax in overview page uses pipe annotations which breaks standard link resolution. Contradictions are documented and reconciled. Recommend: (1) batch create missing author entities, (2) fix link casing in source pages, (3) reindex wiki, (4) consider simplifying overview link syntax.

---

## [2026-06-07 HH:MM] lint-fix | standardized entity link casing

- **Fixed entity link inconsistencies** across 15 wiki pages. Canonical entity names now consistently used throughout.
- **Link corrections by entity:**
  1. `[[Fei-Fei Li]]` → `[[Fei-Fei-Li]]` (2 source pages, 1 entity page) — 5 instances
  2. `[[Eric Xing]]` → `[[Eric-Xing]]` (1 source page, 2 entity pages) — 3 instances
  3. `[[Institute of Foundation Models]]` → `[[Institute-of-Foundation-Models]]` (1 source page, 4 entity pages) — 8 instances
  4. `[[Mohamed bin Zayed University of Artificial Intelligence]]` → `[[Mohamed-bin-Zayed-University-of-Artificial-Intelligence]]` (1 source page, 4 entity pages) — 8 instances
  5. `[[National University of Singapore]]` → `[[National-University-of-Singapore]]` (1 source page, 4 entity pages) — 6 instances
  6. `[[University of Oxford]]` → `[[University-of-Oxford]]` (1 source page, 3 entity pages) — 5 instances
  7. `[[Nanyang Technological University]]` → `[[Nanyang-Technological-University]]` (1 source page, 3 entity pages) — 5 instances
  8. `[[Carnegie Mellon University]]` → `[[Carnegie-Mellon-University]]` (1 entity page) — 2 instances
  9. `[[UC San Diego]]` → `[[UC-San-Diego]]` (1 entity page) — 2 instances

- **Pages modified:** 15 total
  - Source pages (4): [[sources/from-words-to-worlds-spatial-intelligence]], [[sources/a-functional-taxonomy-of-world-models]], [[sources/critiques-of-world-models]], [[sources/agentic-world-modeling]]
  - Entity pages (11): [[entities/Eric-Xing]], [[entities/Carnegie-Mellon-University]], [[entities/Mohamed-bin-Zayed-University-of-Artificial-Intelligence]], [[entities/Institute-of-Foundation-Models]], [[entities/UC-San-Diego]], [[entities/HKUST]], [[entities/National-University-of-Singapore]], [[entities/University-of-Oxford]], [[entities/Nanyang-Technological-University]]

- **Total link replacements:** 44 wiki-link corrections across all affected pages
- **Canonical naming rule applied:** Entity files use PascalCase with hyphens (e.g., `wiki/entities/Fei-Fei-Li.md`); all wiki links now use matching format `[[Entity-Name]]` with hyphens instead of spaces
- **No ambiguous cases:** All inconsistencies resolved unambiguously to canonical names
- **Verification:** Grep-checked for remaining space-separated variants; zero instances found

- Notes: All entity link casing now standardized. YAML frontmatter in source pages (authors, key_entities) corrected. Entity page cross-references (Related Entities sections) now use canonical names. This resolves the majority of broken entity links identified in the 2026-06-07 16:30 lint report.

## [2026-06-07 17:45] ingest-entities | 45 author entity pages created

- **Operation:** Bulk creation of author entity pages from two world modeling papers
- **Source papers:**
  1. [[sources/agentic-world-modeling]] — 42 authors across institutions
  2. [[sources/critiques-of-world-models]] — 3 new authors (Eric Xing already existed)

- **Pages created (45 total):**
  - Agentic World Modeling (42 authors):
    - [[entities/Meng-Chu]], [[entities/Xuan-Billy-Zhang]], [[entities/Kevin-Qinghong-Lin]], [[entities/Lingdong-Kong]], [[entities/Jize-Zhang]], [[entities/Teng-Tu]], [[entities/Weijian-Ma]], [[entities/Ziqi-Huang]], [[entities/Senqiao-Yang]], [[entities/Wei-Huang]], [[entities/Yeying-Jin]], [[entities/Zhefan-Rao]], [[entities/Jinhui-Ye]], [[entities/Xinyu-Lin]], [[entities/Xichen-Zhang]], [[entities/Qisheng-Hu]], [[entities/Shuai-Yang]], [[entities/Leyang-Shen]], [[entities/Wei-Chow]], [[entities/Yifei-Dong]], [[entities/Fengyi-Wu]], [[entities/Quanyu-Long]], [[entities/Bin-Xia]], [[entities/Shaozuo-Yu]], [[entities/Mingkang-Zhu]], [[entities/Wenhu-Zhang]], [[entities/Jiehui-Huang]], [[entities/Haokun-Gui]], [[entities/Haoxuan-Che]], [[entities/Long-Chen]], [[entities/Qifeng-Chen]], [[entities/Wenxuan-Zhang]], [[entities/Wenya-Wang]], [[entities/Xiaojuan-Qi]], [[entities/Yang-Deng]], [[entities/Yanwei-Li]], [[entities/Mike-Zheng-Shou]], [[entities/Zhi-Qi-Cheng]], [[entities/See-Kiong-Ng]], [[entities/Ziwei-Liu]], [[entities/Philip-Torr]], [[entities/Jiaya-Jia]]
  - Critiques of World Models (3 new authors):
    - [[entities/Mingkai-Deng]], [[entities/Jinyu-Hou]], [[entities/Zhiting-Hu]]

- **Pages updated:**
  - [[wiki/index.md]] — Updated total_entities count from 17 to 62; reorganized Entities section into People, Organizations, Universities categories

- **Author affiliations extracted:**
  - HKUST (12 authors): Meng Chu, Zhefan Rao, Jinhui Ye, Xichen Zhang, Wenhu Zhang, Jiehui Huang, Haokun Gui, Haoxuan Che, Long Chen, Qifeng Chen, Jiaya Jia
  - National University of Singapore (11 authors): Xuan Billy Zhang, Lingdong Kong, Teng Tu, Weijian Ma, Yeying Jin, Xinyu Lin, Leyang Shen, Wei Chow, Mike Zheng Shou, See-Kiong Ng
  - University of Oxford (3 authors): Kevin Qinghong Lin, Jize Zhang, Philip Torr
  - Nanyang Technological University (5 authors): Ziqi Huang, Qisheng Hu, Wenya Wang, Ziwei Liu
  - Chinese University of Hong Kong (6 authors): Senqiao Yang, Bin Xia, Shaozuo Yu, Mingkang Zhu, Yanwei Li
  - University of Hong Kong (3 authors): Wei Huang, Shuai Yang, Xiaojuan Qi
  - University of Washington (3 authors): Yifei Dong, Fengyi Wu, Zhi-Qi Cheng
  - Singapore University of Technology and Design (1 author): Wenxuan Zhang
  - Singapore Management University (1 author): Yang Deng
  - Carnegie Mellon University (2 authors): Mingkai Deng, Jinyu Hou
  - UC San Diego (1 author): Zhiting Hu

- **Entity structure:**
  - All authors created with canonical PascalCase-with-hyphens naming (e.g., [[Meng-Chu]], [[Xuan-Billy-Zhang]])
  - Each author page includes: affiliation link, research area tags, source paper links
  - Frontmatter includes `sources` field linking to the paper they authored
  - Related Entities section links back to institutional affiliation entities

- **Relationship connections established:**
  - All 45 author entities now linked from source paper YAML `authors:` fields
  - Reciprocal links from author pages back to their papers via `sources:` and Claims by Source sections
  - Institutional affiliation links wired (e.g., author → HKUST entity)

- **Contradictions found:** None (new entities do not contradict existing content)

- **Notes:** This bulk operation resolves the lint report's finding of 36 broken links pointing to not-yet-created author entities. All author names now have canonical entity pages. Next step: verify institutional entity pages have reciprocal author links if needed.

