# How to read this guidebook

> This page defines the reading and navigation principles of the guidebook.

This guidebook is not intended to be read linearly.  
It is a structured reference for reasoning about the governance and evolution of software systems.

Different readers will engage with different parts depending on their role, intent, and level of familiarity.  
This page establishes the interpretive framework for using the guidebook correctly.

---

## 1. Purpose and reading posture

The guidebook is designed as a disciplined reference, not as a narrative exposition.

It supports:

- Selective consultation  
- Iterative refinement of understanding  
- Role-dependent entry points  

Readers are expected to move between sections, revisit definitions, and use concepts as stable anchors for reasoning.

Linear reading is possible but not assumed.

---

## 2. Two complementary structures

The initiative comprises two complementary but distinct structures:

- **The guidebook** — the exposition of the discipline of Upstream Software Engineering.
- **The guidebook governance framework** — the rules, procedures, and criteria that govern how the guidebook itself is maintained and evolved.

This page concerns the guidebook as read by practitioners, researchers, and decision-makers.

The governance framework is relevant to contributors and editors.  
Its purpose is to ensure conceptual coherence, stability, and controlled evolution.

---

## 3. Conceptual architecture

The structure of the guidebook reflects the conceptual architecture of the discipline.

Concepts are introduced at higher levels of abstraction and refined progressively.  
Subsections clarify, specialize, or operationalize parent concepts.

The organization is therefore not editorial convenience.  
It encodes the decomposition of the discipline into coherent conceptual areas.

Cross-references indicate conceptual relationships.  
They do not necessarily imply containment or hierarchy.

Reading the guidebook means traversing a conceptual structure.

---

## 4. Normativity and compliance

Not all content in the guidebook carries the same normative force.

Three categories are distinguished:

### Normative

Normative content defines what is considered valid within the discipline.

It establishes:

- The scope of the discipline  
- The metamodel and its constraints  
- The valid transformation patterns (plays)  

Normative content is located in **Foundations**.

Compliance with the discipline is assessed exclusively against this content.

### Guiding

Guiding content provides recommended ways of enacting the normative core in real contexts.

It may suggest:

- Representations  
- Artifacts  
- Practices  
- Organizational patterns  

Guiding content is located in **Guidelines**.

It does not impose obligations.  
Multiple enactments may conform equally to the same normative core.

### Informative

Informative content provides context, motivation, or reusable materials.

It includes:

- The problem space that motivates the discipline  
- Downloadable or referential resources  

Informative content carries no normative force.

---

## 5. Structural parts of the guidebook

The guidebook is organized into four main parts, each with a distinct epistemic role:

### Motivation — Informative / Pre-normative

Explains why Upstream Software Engineering is needed.  
Describes the problem space and the limitations observed in current practice.

It prepares the reader but does not define validity.

### Foundations — Normative

Defines the core of the discipline.

It includes:

- The formal definition of the discipline  
- The metamodel  
- The plays (valid transformations)

Foundations answer:

> What is considered valid within this discipline?

### Guidelines — Guiding

Provides recommended ways of enacting the normative core in practical contexts.

Guidelines are adaptable and optional, provided conformity to Foundations is preserved.

### Resources — Informative

Provides reusable materials such as white papers, templates, canvases, and related artifacts.

Resources support application but do not define validity.

---

## 6. Page types and epistemic roles

Within parts, pages serve distinct epistemic functions.

### Concept Definition pages

Provide precise and stable normative anchors.  
They establish the canonical vocabulary of the discipline.

### Rationale pages

Explain why definitions were adopted.  
They analyze relevant literature and extract essential aspects that shaped the definition.

### Usage & Relations pages

Clarify interpretation and application.  
They discuss relationships to other concepts and to external frameworks.

When studying a concept deeply, the recommended sequence is:

1. Definition  
2. Rationale  
3. Usage & Relations  

This separation prevents confusion between validity, justification, and application.

---

## 7. Analytical usage

The guidebook functions as an analytical instrument.

Its concepts can be used to:

- Evaluate governance approaches  
- Clarify system and portfolio boundaries  
- Analyze transformation patterns  
- Compare methodological families  
- Identify structural gaps in existing practices  

Concepts are designed to operate as lenses.

The guidebook supports disciplined reasoning rather than procedural instruction.

---

## 8. Navigation and reading strategies

Different readers may adopt different entry points.

### First-time readers

Start with **Motivation**, then proceed to **Foundations**.

### Architects and technical leads

Use **Foundations** as a reference model.  
Consult **Guidelines** selectively when translating concepts into practice.

### Governance roles

Focus on **Foundations**, especially the plays.  
Use Guidelines to contextualize enactment choices.

### Researchers and educators

Read Foundations in full.  
Treat Guidelines and Resources as supporting material.

Iterative reading and revisiting definitions is expected.

---

## 9. Using the guidebook in context

The guidebook itself is not a project deliverable.

Concrete outputs—such as internal models, documents, or customer-facing artifacts—are created outside the guidebook.

The guidebook defines:

- Conceptual structures  
- Valid transformations  
- Recommended enactment patterns  

Their instantiation is always context-dependent.

---

## 10. Governance and evolution

The guidebook evolves under explicit governance.

Each released version represents a stable and reviewable state.

Changes are introduced incrementally.  
Prior versions remain valid references.

Normative claims must always reference a specific version.

Conceptual stability is intentional and deliberate.

---

## 11. Active reading

The guidebook assumes intellectual engagement.

Readers are encouraged to:

- Compare definitions with their existing mental models  
- Trace implications across conceptual boundaries  
- Examine tensions between frameworks  
- Identify implicit assumptions in current practices  

The guidebook rewards disciplined and reflective reading.

---

## Summary

- The guidebook encodes the conceptual architecture of a discipline.  
- Foundations define validity.  
- Guidelines support enactment without imposing obligations.  
- Motivation and Resources provide context.  
- Page types distinguish definition, justification, and application.  
- Reading paths depend on role and intent.  
- Versions matter.  

Use this guidebook as a structured instrument for reasoning about the governance and evolution of software systems.


---
---


# How to read this guidebook

> This page defines the reading and navigation principles of the guidebook.

This guidebook is not intended to be read linearly.

It is designed as a **reference for reasoning and governance**, where different readers may engage with different parts depending on their role, intent, and level of familiarity.

This page defines the **rules of interpretation** for the entire guidebook.



## The structure of the guidebook

The guidebook is organized into four main **parts**:

- Motivation
- Foundations
- Guidelines
- Resources

Each part has a distinct role and carries a different normative weight.

Understanding these distinctions is essential for using the guidebook correctly.


## The role of each part


### Motivation

The **[Motivation](./motivation/index.md)** part explains **why Upstream Software Engineering is needed**.

It describes the problem space and the limitations observed in current practice that motivate the formulation of a dedicated discipline to govern software systems over time.

Motivation is **pre-normative**.

It prepares the reader for the definitions introduced later, but it does not define validity or impose obligations.


### Foundations

The **[Foundations](./foundations/index.md)** part defines the **normative core** of Upstream Software Engineering.

It includes:

- **[The discipline](./foundations/discipline/index.md)** — the formal definition of Upstream Software Engineering, including its scope and boundaries
- **[The metamodel](./foundations/metamodel/index.md)** — the normative conceptual structure that defines the concepts, relationships, and constraints used to reason about software systems and their evolution
- **[The plays](./foundations/plays/index.md)** — the valid transformation patterns that operate over models conforming to the metamodel

Foundations answer the question:

> What is considered valid within this discipline?

Statements in this part are **normative**.

Compliance is assessed **only** against Foundations.


### Guidelines

The **[Guidelines](./guidelines/index.md)** part provides **recommended ways** to enact the Foundations in practice.

It includes:

- **[The artifacts](./guidelines/artifacts/index.md)** — suggested ways of representing, documenting, or managing models that conform to the metamodel
- **[The practices](./guidelines/practices/index.md)** — situational ways of executing plays in concrete organizational contexts

Guidelines answer the question:

> How can the normative core be enacted in real contexts?

Content in this part is **non-normative**.

Guidelines are optional and adaptable.

Different practitioners and tool builders may choose different representations, as long as the underlying models conform to the metamodel defined in the **Foundations**.


### Resources

The **[Resources](./resources/index.md)** part provides **downloadable and reusable materials** produced as part of this initiative.

It includes white papers, research papers, books, templates, canvases, multimedia, and other artifacts intended to be used, adapted, or cited.

Resources are **informative only** and have **no normative force**.


## Normativity and compliance

Not all content in this guidebook has the same normative force.

- **Normative**
  - Discipline
  - Metamodel
  - Plays

- **Guiding**
  - Artifacts
  - Practices

- **Informative**
  - Motivation
  - Resources

Only the content in **Foundations** defines validity.

Only Foundations are subject to compliance assessment.

Guidelines may inform governance decisions, but they do not impose obligations.


## Language and interpretation

Language is used deliberately.

- Normative statements describe what *is* or what *is considered valid*
- Guiding statements describe what *may be useful*, *common*, or *recommended*
- Informative content provides context and support

Recommendations should not be interpreted as requirements.


## How to navigate the guidebook

The guidebook supports multiple reading paths.

- **First-time readers**  
  Start with this page, then read **[Motivation](./motivation/index.md)**.

- **Architects and technical leads**  
  Use **[Foundations](./foundations/index.md)** as a reference; consult **[Guidelines](./guidelines/index.md)** selectively.

- **Governance roles**  
  Focus on **[Foundations](./foundations/index.md)** → **[The plays](./foundations/plays/index.md)**, using **[Guidelines](./guidelines/index.md)** for context.

- **Researchers and educators**  
  Read **[Foundations](./foundations/index.md)** in full; treat **[Guidelines](./guidelines/index.md)** and **[Resources](./resources/index.md)** as supporting material.

Selective and iterative reading is expected.


## Using the guidebook in context

The guidebook itself is **not a deliverable**.

Concrete outputs—such as project documents, internal representations, or customer-facing materials—are created **outside** the guidebook.

The guidebook defines:

- the conceptual structures
- the valid transformations
- and recommended ways of working

Their instantiation is always **context-dependent**.


## Versions and evolution

This guidebook evolves over time.

Each released version represents a **stable and reviewable state**.

Changes are introduced incrementally, and prior versions remain valid references.

Readers should always consider **which version** is being used when making normative claims.


## Summary

In summary:

- Use this page to understand **how to interpret the guidebook**
- Read **[Motivation](./motivation/index.md)** to understand why the discipline is needed
- Use **[Foundations](./foundations/index.md)** to assess validity
- Consult **[Guidelines](./guidelines/index.md)** for practical inspiration
- Use **[Resources](./resources/index.md)** for reusable materials and further application

This separation enables governance **without rigidity**, and guidance **without prescription**.


## Where to go next

↖ Return to **[Guidebook](./)** for the purpose, scope, and structure of this guidebook.
