# Upstream Software Engineering

> This page introduces the guidebook for the practice of Upstream Software Engineering, the epistemic governance of the intent of long-lived software systems.


## About Upstream Software Engineering

Upstream Software Engineering is the practice of epistemic governance of the intent of long-lived software systems.

Long-lived software systems are enduring socio-technical entities whose governing commitments persist across initiatives, teams, technological shifts, and organizational restructuring.  Yet the knowledge that defines their intent — their commitments about scope, structure, constraints, and non-goals — is often fragmented or implicit.

When those commitments are not explicitly governed, intent fragments, drifts, or is repeatedly reconstructed.  Evolution then becomes increasingly effortful and uncertain.  While change may be intrinsically complex, instability or ambiguity in governing commitments amplifies that complexity and obscures what must remain valid.

Upstream Software Engineering addresses this condition.  It establishes durable and revisable commitments about scope and structure, clarifies authority and stewardship over those commitments, and defines the conditions under which change is considered valid.  It governs intent without prescribing implementation.

The discipline complements development methodologies, architectural practices, and operational frameworks.  It does not replace them.  Instead, it provides the normative reference within which downstream realization and long-term evolution remain coherent across time..


## About this guidebook

### What this guidebook is

This guidebook is the authoritative articulation of the practice of Upstream Software Engineering.

It establishes the conceptual and normative framework through which the intent of long-lived software systems is governed.  It formalizes the commitments, structures, and transformation patterns that define valid upstream practice, and distinguishes them from downstream realization activities.


### What this guidebook is not

This guidebook is not a methodology for software development, a project management framework, or an operational playbook.

It does not prescribe implementation techniques, delivery processes, or runtime operations.  It does not replace downstream engineering practices, nor does it dictate how systems must be constructed in specific technological contexts.

Its concern is upstream: the governance of intent, commitments, and structural validity that normatively guide downstream realization without determining it.


### Questions addressed by this guidebook

This guidebook frames and answers questions such as:

- What is the software system beyond its current implementation?
- In which context does it exist and evolve?
- Which commitments are valid, and which are not?
- How are upstream commitments articulated, justified, revised, and made durable over time?


### What this guidebook provides

This guidebook provides the normative and conceptual reference for practicing Upstream Software Engineering.

It defines the concepts, relationships, and validity conditions that govern upstream commitments, and specifies the transformation patterns through which those commitments evolve over time.

It also offers non-normative guidance for enacting the discipline within concrete organizational contexts.


### How this guidebook relates to practice

This guidebook does not replace concrete organizational artifacts or delivery processes.

Instead, it establishes the upstream commitments that those artifacts and processes are expected to respect.

Project-specific documents, working notes, contractual agreements, and implementation decisions exist outside this guidebook. They instantiate upstream commitments within specific technological and organizational contexts.

The guidebook defines what is valid at the level of intent and structure; its enactment belongs to the practice of the discipline.



## What this guidebook is

This guidebook is the authoritative articulation of the practice of Upstream Software Engineering.

It establishes the conceptual and normative framework through which the intent of long-lived software systems is governed.  It formalizes the commitments, structures, and transformation patterns that define valid upstream practice, and distinguishes them from downstream realization activities.


## What this guidebook is not

This guidebook is not a methodology for software development, a project management framework, or an operational playbook.

It does not prescribe implementation techniques, delivery processes, or runtime operations.  It does not replace downstream engineering practices, nor does it dictate how systems must be constructed in specific technological contexts.

Its concern is upstream: the governance of intent, commitments, and structural validity that normatively guide downstream realization without prescribing its implementation.





## What this guidebook is

This guidebook presents a framework for **Upstream Software Engineering**:  the discipline concerned with **defining, governing, and evolving software systems** before and across their realization.

It addresses questions such as:

- What is the software system, beyond its current implementation?
- In which context does it exist and evolve?
- Which changes are valid, and which are not?
- How are decisions justified, recorded, and revisited over time?

This guidebook contains both normative definitions and non-normative guidance.  Normative content defines what is considered valid within the discipline.  Guidance supports interpretation and enactment, but does not establish validity.


## What this guidebook is not

This guidebook is not:

- a development methodology
- a project management framework
- a set of mandatory documents or procedures
- a replacement for downstream engineering practices

It does not prescribe downstream engineering practices, implementation techniques, or operational procedures.  Instead, it focuses on the **intent, constraints, and transformations** that downstream activities are expected to respect.


## How the guidebook is organized

The guidebook is organized into four main **parts**, each with a distinct role.


### Motivation

The **[Motivation](./motivation/index.md)** part explains **why Upstream Software Engineering is needed**.

It describes the problem space and the limitations observed in current practice that motivate the need for a dedicated discipline to govern software systems over time.

This part prepares the reader for the normative definitions introduced in the Foundations.


### Foundations

The **[Foundations](./foundations/index.md)** part defines the **normative core** of Upstream Software Engineering.

It contains:

- **[The discipline](./foundations/discipline/index.md)** — the formal definition of Upstream Software Engineering, including its scope and boundaries.
- **[The metamodel](./foundations/metamodel/index.md)** — the normative conceptual structure that defines the concepts, relationships, and constraints used to reason about software systems and their evolution.
- **[The plays](./foundations/plays/index.md)** — the valid transformation patterns that operate over models conforming to the metamodel.

Foundations define **what is considered valid**.  Compliance is assessed against this part.


### Guidelines

The **[Guidelines](./guidelines/index.md)** part provides **recommended ways** to enact the **Foundations** in practice.

It contains:

- **[The artifacts](./guidelines/artifacts/index.md)** — suggested ways of representing, documenting, or managing models that conform to the metamodel.
- **[The practices](./guidelines/practices/index.md)** — situational ways of executing plays in concrete organizational contexts.

Guidelines are **non-normative**.  
They are meant to be adapted, combined, or replaced as needed.

Different practitioners and tool builders may choose different representations, as long as the underlying models conform to the metamodel defined in **Foundations**.


### Resources

The **[Resources](./resources/index.md)** part provides **downloadable and reusable materials** produced as part of this initiative.

It includes white papers, research papers, books, templates, canvases, multimedia, and other artifacts that support learning, application, and dissemination of Upstream Software Engineering.

Resources are **informative only** and have **no normative force**.


## How to read this guidebook

This guidebook is not meant to be read linearly.

↘ Refer to [How to read this guidebook](./how-to-read.md) for the principles that govern interpretation, normativity, navigation, and compliance across the guidebook.

That page functions as the reader’s contract for the entire guidebook.


## Versioning and evolution

This guidebook evolves over time.

- Each released version is frozen
- The current version reflects the latest accepted state
- Future changes are introduced incrementally and transparently


## Contributing

This guidebook evolves through structured and governed change.

Contributions — including proposals for new definitions, refinements to existing concepts, extensions of analyses, or structural adjustments — are subject to explicit editorial governance.

↗ See **[Guidebook governance](./meta/)** for the governance framework that regulates the structure, authorship, evolution, and authority of the guidebook.


## Intended audience

This guidebook is intended for professionals and researchers involved in the **definition, governance, and long-term evolution of software systems**, including the following.


### Product and technology leadership

- software architects
- technical leads and principal engineers
- product leads and product managers
- engineering managers responsible for product direction


### Governance and organizational roles

- roles responsible for product, portfolio, or architectural governance
- decision-makers defining boundaries, ownership, and accountability
- consultants supporting organizations in software system governance and evolution


### Software Engineering practice (upstream-focused)

- senior software engineers involved in architectural and structural decisions
- practitioners operating across multiple teams, systems, or providers
- roles bridging business intent and technical realization


### Research and education

- researchers studying software systems, evolution, and governance
- educators designing curricula or teaching advanced software engineering topics
- students learning how to govern long-lived software systems

This guidebook assumes familiarity with:

- Software Engineering concepts and terminology
- modern software development practices
- organizational contexts where software systems evolve over time

It is **not intended as an introductory text** to software development.


## How this guidebook relates to practice

Concrete applications of this guidebook — including:

- project-specific documents
- internal working notes
- customer deliverables

exist **outside** this guidebook.

The guidebook defines:

- the conceptual structures
- the valid transformations
- and recommended ways of working

Their instantiation belongs to the context in which they are applied.


## Where to go next

If you are new to the guidebook, proceed in the following order:

1. **[How to read this guidebook](./how-to-read.md)** — to understand interpretation and normativity  
2. **[Motivation](./motivation/index.md)** — to understand why the discipline is needed  
3. **[Foundations](./foundations/index.md)** — to explore the discipline, its metamodel, and its plays  

Use **[Guidelines](./guidelines/index.md)** as a source of inspiration and operational advice.  

Consult **[Resources](./resources/index.md)** for reusable materials you can download or adapt.
