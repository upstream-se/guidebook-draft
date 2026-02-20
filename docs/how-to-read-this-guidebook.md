# How to read this guidebook

> This page defines the reading and navigation principles of the guidebook.

This guidebook is not intended to be read as a linear narrative.

It is a structured reference designed to support disciplined reasoning about the governance and evolution of long-lived software systems.  Its organization reflects the architecture of the discipline it presents, rather than a sequential exposition.

Not all content in the guidebook carries the same normative force.  Some sections define what is considered valid within the discipline, while others provide guidance, context, or supporting material.  Understanding these distinctions is essential for interpreting the guidebook correctly.

Readers may enter the guidebook from different points depending on their role, objectives, and familiarity with the subject.  Concepts are refined progressively, and sections are meant to be revisited as understanding deepens.

This page explains how to interpret the structure of the guidebook, how to distinguish between different types of content, and how to navigate it effectively.


## Purpose and reading posture

The guidebook presents Upstream Software Engineering as the discipline concerned with the governance of the intent of long-lived software systems.  It articulates the constructs used to express that intent on the scope and structural decisions and constraints within which the system is framed, and the transformation patterns that operate over it.

The guidebook contains a normative core.  Certain elements are defined as valid within the discipline, and these definitions are constitutive of adherence to it.  Compliance is therefore conceptually checkable.  At the same time, the guidebook is not issued by a formal standards body and does not derive its authority from institutional regulation, but from the internal coherence and explicit structure of the discipline it presents.

The guidebook is not a cookbook that provides predefined recipes for recurring situations, nor a playbook that enumerates prescribed moves to be executed in sequence, nor a handbook that documents operational procedures for routine execution.  It does not define a single mandatory workflow to be applied uniformly across contexts.  Instead, it integrates normative foundations with structured recommendations, maintaining a clear distinction between what is required for validity and what is suggested as a way of working.

Accordingly, the guidebook is intended to support disciplined judgment rather than mechanical execution.  It should be consulted selectively, its definitions revisited when needed, and its distinctions used to guide reasoning and decision-making in concrete contexts.


## Two complementary artifacts

The initiative comprises two complementary but distinct artifacts: the Guidebook and the Guidebook Contributors Guide.

The Guidebook presents the discipline of Upstream Software Engineering.  It defines its constructs, normative core, and recommended ways of working.  It is addressed to practitioners, architects, researchers, and decision-makers who engage with the discipline.

The Guidebook Contributors Guide defines how the Guidebook itself is constructed, reviewed, versioned, and evolved.  It specifies the structural, editorial, and lifecycle rules that govern contributions and changes.  It is addressed to those who maintain and develop the Guidebook as an intellectual artifact.  Reading the Guidebook Contributors Guide is not required to understand, adhere to, or enact the discipline; it is relevant only to those participating in the Guidebook’s maintenance and evolution.  

This page is intended for readers engaging with the discipline through the guidebook.

↗ See **[Guidebook Contributors Guide](../meta/)** for the procedural and structural rules governing the construction and evolution of the guidebook.


## Conceptual architecture

The guidebook encodes a structured conceptual articulation of the discipline.  Its hierarchy is not merely expository; it reflects normative relationships of containment and specialization between concepts.

Parent pages introduce broader conceptual domains.  Child pages refine or specialize those domains by adding constraints, distinctions, or structured elaboration.  Pages at the same hierarchical level represent alternative refinements within a shared conceptual scope.  The hierarchy therefore expresses how concepts relate to one another within the articulated system of the guidebook.

Not all conceptual relationships are hierarchical.  Some pages clarify, expand, or complement others without constituting specialization.  These relationships are expressed through cross-references rather than structural containment.

Navigation arrows signal these relationships.  Downward arrows indicate refinement; upward arrows indicate return to a broader conceptual domain; horizontal arrows indicate movement across related refinements; diagonal arrows indicate contextual or complementary references.  These symbols are part of the guidebook’s structural language and assist readers in interpreting conceptual relationships across pages.


## Normativity and compliance

Not all content in the guidebook has the same normative status.

The guidebook distinguishes between normative, guiding, and informative content.

**Normative content** defines what is considered valid within the discipline.  It establishes the constructs, distinctions, and transformation patterns that are constitutive of adherence.  Claims of conformity to the discipline are evaluated against this normative core.  Only normative content is subject to compliance assessment.

**Guiding content** provides recommended ways of working with the normative elements.  It suggests structured practices, representations, and approaches, but it does not impose a single mandatory procedure.  Multiple enactments may remain valid provided they conform to the normative core.  Guiding content is not subject to compliance assessment.

**Informative content** provides context, explanation, or supporting material.  It assists understanding but does not define validity and is not subject to compliance assessment.

Understanding these distinctions is essential for correct interpretation.  Normative content defines compliance; guiding and informative content support reasoning and enactment.


## Structural parts of the guidebook

The guidebook is organized into four main parts.  Each part has a distinct epistemic role and normative status.


### Motivation — Informative

The Motivation part articulates the problem space within which the discipline emerges.  It identifies recurring challenges, examines the limits of existing approaches, and explains why an upstream perspective is warranted.  Its function is justificatory: it frames and rationalizes the need for the normative core defined in Foundations.  It does not define validity and is not subject to compliance assessment.


### Foundations — Normative

The Foundations part defines the normative core of the discipline.  It specifies the scope of Upstream Software Engineering, the constructs used to articulate intent, and the valid transformation patterns that operate over them.  Foundations are constitutive of adherence.  Only this part defines what is considered valid within the discipline and is subject to compliance assessment.


### Guidelines — Guiding

The Guidelines part provides structured recommendations for working with the normative core defined in Foundations.  It includes suggested artifacts, practices, roles, and organizational patterns that reify and operationalize the discipline’s constructs.

Guidelines assist in structuring activity, organizing responsibilities, and shaping decision-making contexts.  They support enactment of the discipline but do not define validity.  Conformity to the discipline is evaluated against Foundations, not against the specific practices or artifacts described in Guidelines.


### Resources — Informative and Guiding

The Resources part provides supporting materials, such as papers, templates, tutorials, and related artifacts.  Depending on their nature, these materials may be informative (providing context or explanation) or guiding (offering examples or structured assistance).  Resources do not define validity and are not subject to compliance assessment.


## Page types and epistemic roles

Pages in the guidebook are classified along two distinct dimensions: structural type and epistemic role.


### Structural page types

The content model defines structural page types that regulate how pages are organized and related within the guidebook:

- **Container pages** aggregate and contextualize related pages within the primary hierarchy.
- **Content pages** develop a focused conceptual, normative, or procedural unit.
- **Complementary pages** supplement other pages without belonging to the primary hierarchy.

Structural type determines how a page participates in the guidebook’s architecture and navigation.


### Epistemic roles

Separate from structural type, pages also fulfill epistemic roles.  These roles describe the function the content plays within the discipline — for example, defining a concept, stating a principle, providing justification, or clarifying usage.

Epistemic roles are declared through structured callouts within the page content.  These callouts are marked with a solid square symbol (■) followed by a title that signals the role of the content.  Structured callouts titled *Definition* or *Principle*, among others, are widely used in the guidebook.  A page may contain multiple structured callouts and therefore fulfill multiple epistemic roles.

Structural type determines how a page is positioned within the guidebook; structured callouts determine how its content should be interpreted.


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
