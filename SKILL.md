---
name: scientific-writing-engine
description: Scientific writing, paragraph rewriting, and peer-review editing engine based on empirical analysis of high-impact biomedical and organoid research teams. Organizes problem-driven logic, figure-driven results storytelling, mechanism-bounded discussion, and rigorous academic English.
---

# Scientific Writing Engine

A reusable, execution-ready skill for drafting, rewriting, structuring, and reviewing high-impact biomedical manuscripts, research proposals, and abstracts.

## Empirical Foundation & Scope

The **Scientific Writing Engine** is grounded in a systematic analysis of 20 representative, high-impact publications (2014–2026) spanning *Advanced Science*, *Biomaterials*, *Lab on a Chip*, *ACS Biomaterials Science & Engineering*, *Science Bulletin*, and *BMC Pharmacology and Toxicology*. It extracts invariant rhetorical structures, scientific argument progressions, and syntactic pacing, making them directly applicable to:
- Parkinson's disease (PD), Alzheimer's disease (AD), and neurodegenerative brain organoid models.
- Intestinal organoids, gut barrier pathology, and inflammatory bowel disease (IBD).
- RNA-small molecule interactions, chemical biology, and targeted molecular therapeutics.
- Multi-organ physiological axes, blood-brain barrier (BBB) integrity, and microphysiological disease modeling.

---

## Foundational Principle: Complete Content & Style Separation

1. **Scientific Content Layer**:
   - Scientific facts, experimental measurements, statistical thresholds, cell types, specific genes/proteins, and literature references are supplied **strictly by the user** or verified domain literature.
   - The engine never fabricates data, invents biological pathways, or extrapolates beyond user-provided experimental evidence.
2. **Writing Style Layer**:
   - Rhetorical funneling, paragraph topic-sentence placement, figure-driven narrative arcs, epistemic claim bounding, and syntactic conciseness are enforced by this engine.

---

## The 10 Invariant Scientific Writing Rules

### Rule 1: The 4-Stage Problem-Driven Funnel (Introduction)
- **Structure**:
  - *Stage 1 (Clinical/Biological Imperative)*: Establish disease burden, affected anatomical compartment, and pathological hallmark.
  - *Stage 2 (Model Evolution & Interspecies Divergence)*: Credit existing 2D/rodent models while exposing their fatal translational boundaries.
  - *Stage 3 (The Precise Mechanistic Bottleneck)*: Pinpoint the exact missing dimension (e.g., lack of hemodynamic perfusion, missing immune-vascular crosstalk, or absent multi-organ endocrine coupling).
  - *Stage 4 (Strategic Intervention & Core Discoveries)*: Present the study's engineered platform as the purpose-built solution and summarize primary phenotypic/mechanistic findings.
- **Reference**: `references/introduction-patterns.md`.

### Rule 2: The 6-Act Macro Results Storyline Arc
- **Structure**: Organize the overall Results narrative into 6 progressive biological milestones:
  $$\text{Act 1 (Validation)} \rightarrow \text{Act 2 (Cytoarchitecture)} \rightarrow \text{Act 3 (Physiology/Transport)} \rightarrow \text{Act 4 (Pathology)} \rightarrow \text{Act 5 (Omics/Mechanism)} \rightarrow \text{Act 6 (Rescue)}$$
- **Reference**: `references/results-patterns.md`.

### Rule 3: The Micro-Syllogism of Individual Results Paragraphs (The 6-Element Unit)
- **Structure**: Every Results paragraph must follow this sequential progression:
  1. *Biological Rationale / Hypothesis Lead-in* (*"To determine whether..."*)
  2. *Experimental Setup & Figure Call* (*"...organoids were exposed to... (Figure XA)"*)
  3. *Primary Qualitative Observation* (*"Immunostaining revealed..."*)
  4. *Rigorous Quantitative Data & Statistics* (*"Quantification confirmed a 3.5-fold decrease... p < 0.001"*)
  5. *Intermediate Biological Inference* (*"These data demonstrate that..."*)
  6. *Forward Narrative Bridge* (*"Prompted by this marked loss, we next interrogated..."*)

### Rule 4: Claim-Driven Headings & Topic-Sentence Primacy
- **Structure**: Results subsection titles and paragraph openings must declare the scientific insight, not the assay name.
  - *Weak*: "RNA-seq and Western Blot Analysis"
  - *Claim-Driven*: "Transcriptomic Profiling Identifies Aberrant cGAS-STING Activation in Radiated Endothelium"

### Rule 5: Strict Mechanism-Bounded Evidence Hierarchy
- **Epistemic Calibration**:
  - *Observational Data*: `revealed`, `exhibited`, `displayed`, `demonstrated that...`
  - *Correlative Trends*: `correlated with`, `coincided with`, `was accompanied by...`
  - *Causal Mechanism*: `mediates`, `governs`, `is required for`, `abrogates`. **Mandatory Guardrail**: Causal verbs are permitted *only* when substantiated by targeted rescue, genetic knockout, or pharmacological inhibition!

### Rule 6: Quantitative & Statistical Precision
- **Requirement**: Eliminate unsupported subjective intensifiers (e.g., "dramatically increased", "vastly reduced"). State the exact biological metric, fold-change or absolute mean, variance ($\pm \text{SD}$ or $\text{SEM}$), sample size ($n$), and exact $P$-value threshold.

### Rule 7: Discussion Conceptual Synthesis & Epistemic Humility
- **Structure**:
  - *Pillar 1 (Conceptual Synthesis)*: State the overarching paradigm shift without repeating raw percentages or figure numbers.
  - *Pillar 2 (Literature Concordance)*: Contextualize findings against human clinical biopsies and explain discrepancies with animal models.
  - *Pillar 3 (Mechanistic Multi-Hit Synthesis)*: Articulate how the primary pathway intersects with potential secondary loops.
  - *Pillar 4 (Candid Study Limitations)*: Preemptively acknowledge at least 2–3 biological boundaries (e.g., developmental maturity, lack of systemic immune axes, device throughput).
- **Reference**: `references/discussion-patterns.md`.

### Rule 8: Dense Syntactic Packing & Active Scholarly Voice
- **Technique**: Use participial lead-ins, absolute constructions, and high-precision academic verbs (`recapitulate`, `ameliorate`, `abrogate`, `orchestrate`, `elucidate`) to maximize information density and maintain narrative rhythm.
- **Reference**: `references/academic-language-guide.md`.

### Rule 9: Dialectical Contrast & Hypothesis-Driven Transitions
- **Technique**: Thread paragraphs together using logical connectors that articulate causality and contrast (`Consistently`, `Intriguingly`, `Strikingly`, `In contrast to static cultures`, `Prompted by these findings`).

### Rule 10: Strict Narrative & Content Fidelity Guardrail
- **Guardrail**: Never alter experimental values, forge statistical significance, or inject biological hypotheses from unrelated models during editing. When narrative flow requires additional biological evidence, explicitly advise the user to provide it rather than inventing it.

---

## Operational Workflow Modes

1. **Mode 1: Draft from Scratch**: Transform outline notes and raw data into journal-ready Introductions, Results, and Discussions.
2. **Mode 2: Manuscript Rewrite & Structural Polish**: Reorganize sentence order and elevate academic tone while freezing all scientific facts.
3. **Mode 3: Results Storyline Construction**: Map figure panels into the 6-Act narrative arc.
4. **Mode 4: Rigorous Peer-Review & Logical Audit**: Audit drafts for over-extrapolation, ungrounded causal claims, and missing study limitations.
5. **Mode 5: Grant Proposals & Specific Aims**: Apply the funnel structure to grant rationales and research strategies.
