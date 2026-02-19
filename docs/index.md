# Upstream Software Engineering

*A guidebook for governing the construction and evolution of software systems*


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
