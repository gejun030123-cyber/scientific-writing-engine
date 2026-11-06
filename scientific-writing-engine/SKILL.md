---
name: scientific-writing-engine
description: Scientific writing, paragraph rewriting, and peer-review editing engine based on empirical analysis of high-impact biomedical and organoid research teams. Organizes problem-driven logic, figure-driven results storytelling, mechanism-bounded discussion, and rigorous academic English.
---

# Scientific Writing Engine

A reusable, execution-ready skill for drafting, rewriting, structuring, and reviewing high-impact biomedical manuscripts, research proposals, and abstracts.

## Overview & Foundational Architecture

The **Scientific Writing Engine** transforms raw biomedical observations, experimental data points, and outline notes into rigorous, publication-grade academic prose. It enforces a strict **separation between Scientific Content and Writing Style**:
- **Scientific Content Layer**: Biological entities, experimental results, numerical measurements, statistical significance, and literature references are supplied exclusively by user input or verified domain facts.
- **Writing Style Layer**: Narrative structure, topic-sentence placement, figure-driven progression, epistemically calibrated verb choices, and logical transitions are governed by this engine.

---

## The 8 Core Operational Rules

### Rule 1: Problem-Driven Funnel (Introduction)
- **Definition**: The Introduction must narrow strictly from a macro clinical/biological imperative to existing model milestones, a critical unresolved knowledge gap, a strategic bioengineering/experimental approach, and core mechanistic takeaways.
- **Corpus Evidence**: Universal 4–5 paragraph funnel observed across high-impact organoid and microphysiological papers (e.g., P01, P02, P04).
- **Recommended Context**: Manuscript introductions, project background statements, grant specific aims.
- **Reference**: Consult `references/introduction-patterns.md`.

### Rule 2: Figure-Driven Incremental Storytelling (Results)
- **Definition**: Each Results subsection corresponds to a distinct biological milestone, driven by a claim-focused heading and organized into 6-element narrative units: Biological Rationale → Experimental Setup → Qualitative Observation → Quantitative Data & Statistics → Intermediate Biological Inference → Forward Bridge.
- **Corpus Evidence**: Rigorous progressive narrative flow from model establishment to phenotypic profiling, multi-omics interrogation, and targeted intervention (e.g., P02, P03, P06, P07).
- **Recommended Context**: Original research results sections, figure legend drafting, progress report findings.
- **Reference**: Consult `references/results-patterns.md`.

### Rule 3: Mechanism-Bounded Evidence Hierarchy
- **Definition**: Strict linguistic demarcation between observational evidence (`revealed`, `displayed`), correlative trends (`correlated with`, `was accompanied by`), and causal mechanism (`demonstrated that X mediates Y`). Causal assertions are permitted **only** when supported by targeted rescue, genetic knockout, or specific pharmacological inhibition.
- **Corpus Evidence**: Rigorous calibration between phenotype induction and rescue assays (e.g., P01, P02, P09).
- **Recommended Context**: Results interpretations, Discussion synthesis, Abstract conclusions.
- **Reference**: Consult `references/academic-language-guide.md`.

### Rule 4: Claim-Driven Topic Sentence Architecture
- **Definition**: Every paragraph must open with a direct declarative claim summarizing the core insight, followed by 3–5 dense evidential sentences and a concluding biological implication. Never begin a paragraph with an isolated method description or generic transition.
- **Corpus Evidence**: Paragraphs consistently lead with functional statements rather than procedural histories (e.g., P01, P05, P10).
- **Recommended Context**: All scientific manuscript drafting and structural editing.

### Rule 5: Quantitative & Statistical Precision
- **Definition**: Quantitative findings must state the exact biological metric, fold-change or absolute difference, sample variance ($\pm \text{SD}$ or $\text{SEM}$), and statistical significance ($p$-value threshold). Avoid subjective intensifiers like "dramatically increased" or "a huge drop" without accompanying numerical backing.
- **Corpus Evidence**: Standard reporting across all analyzed quantitative figures.
- **Recommended Context**: Results drafting and table/figure integration.

### Rule 6: Discussion Conceptual Synthesis & Epistemic Humility
- **Definition**: The Discussion must avoid regurgitating raw numbers or figure numbers from the Results. It must synthesize the overarching conceptual advance, contextualize findings against human pathology and animal models, explicitly state at least two concrete model limitations (e.g., maturity stage, lack of vascular/immune components), and project actionable translational applications.
- **Corpus Evidence**: Standard structure of Discussion sections in high-impact journals (e.g., P01, P02, P09).
- **Recommended Context**: Manuscript Discussion sections and perspective pieces.
- **Reference**: Consult `references/discussion-patterns.md`.

### Rule 7: Dense Syntactic Packing & Active Voice
- **Definition**: Maximize information density by utilizing participial phrases, absolute constructions, and active, high-precision academic verbs (`recapitulate`, `ameliorate`, `abrogate`, `orchestrate`, `elucidate`). Replace nominalized passive chains with concise active predication.
- **Corpus Evidence**: Elevated syntactic rhythm and conciseness in top-tier publications.
- **Recommended Context**: Manuscript revision, word-count reduction, language polishing.
- **Reference**: Consult `references/academic-language-guide.md`.

### Rule 8: Strict Narrative & Content Fidelity Guardrail
- **Definition**: When polishing or restructuring, never fabricate experimental measurements, alter statistical significance, invent biological pathways, or import unverified mechanisms from other organ systems. When a narrative gap exists, explicitly highlight it as a recommendation for user input rather than inventing speculative data.
- **Corpus Evidence**: Ethical standard across academic peer review.
- **Recommended Context**: Automated text polishing, translation, and peer-review auditing.

---

## Five Standard Operational Scenarios

### Scenario 1: Drafting from Scratch (De Novo Manuscript Writing)
1. **User Input**: Outline notes, experimental protocols, raw measurements, target journal.
2. **Execution Steps**:
   - Step 1: Formulate the 5-part Introduction Funnel (`references/introduction-patterns.md`).
   - Step 2: Establish claim-driven Results headings and arrange figures into a 6-act narrative arc (`references/results-patterns.md`).
   - Step 3: Populate each Results subsection using the 6-element sentence sequence.
   - Step 4: Draft Discussion emphasizing literature alignment, evidence boundaries, and candid limitations (`references/discussion-patterns.md`).

### Scenario 2: Existing Manuscript Rewriting & Structural Polish
1. **User Input**: Rough draft or translated manuscript.
2. **Execution Steps**:
   - Step 1: Conduct a Content Fidelity Check to freeze all scientific facts, numerical values, and citations.
   - Step 2: Reorganize paragraph sequence to eliminate fragmented listings and establish strong topic sentences.
   - Step 3: Replace weak/colloquial phrasing using the High-Precision Academic Verb Matrix (`references/academic-language-guide.md`).
   - Step 4: Calibrate epistemic claims against experimental evidence (Rule 3).

### Scenario 3: Figure-Driven Results Storyline Construction
1. **User Input**: List of figure panels, assays performed, and primary observations.
2. **Execution Steps**:
   - Step 1: Sort figures into a logical progression: Validation $\rightarrow$ Phenotype $\rightarrow$ Multi-omics $\rightarrow$ Rescue.
   - Step 2: Generate claim-driven subsection titles declaring the biological takeaway of each panel group.
   - Step 3: Build narrative bridging transitions connecting preceding findings to subsequent rationales.

### Scenario 4: Rigorous Peer-Review & Logical Audit
1. **User Input**: Draft manuscript.
2. **Execution Steps**:
   - Check A: Does the Introduction identify an authentic mechanistic knowledge gap or just a descriptive novelty?
   - Check B: Are Results claims strictly supported by the data (e.g., was a causal verb used without a rescue experiment)?
   - Check C: Does the Discussion rehash raw numbers from the Results instead of providing conceptual synthesis?
   - Check D: Are study limitations candidly articulated?

### Scenario 5: Research Proposal & Grant Writing
1. **User Input**: Specific aims, preliminary data, clinical problem.
2. **Execution Steps**:
   - Structure the Significance section using the Funnel Architecture (Clinical urgency $\rightarrow$ Current limitations $\rightarrow$ Proposed breakthrough).
   - Formulate Specific Aims with active, hypothesis-driven headers (`Aim 1: Interrogate the role of...`, `Aim 2: Decipher the molecular cascade...`).
   - Detail experimental design with explicit risk mitigation and alternative strategies.

---

## Quality Checklist Before Final Output Delivery

- [ ] **Content Integrity**: Are all scientific facts, fold-changes, and $p$-values identical to user inputs?
- [ ] **No Hallucinated Data**: Have all unverified biological pathways or measurements been avoided?
- [ ] **Topic Sentence Clarity**: Does every paragraph open with a strong, active claim?
- [ ] **Claim Calibration**: Are verbs strictly matched to evidence tier (observational vs. causal)?
- [ ] **Bridging Transitions**: Do consecutive subsections and paragraphs flow smoothly without abrupt thematic leaps?
- [ ] **No Superlatives**: Are boastful or non-academic terms ("revolutionary", "perfectly", "unrivaled") eliminated?
