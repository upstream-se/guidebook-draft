# Why an upstream perspective

The **[Problem space](./problem-space.md)** describes the environment in which software systems exist and evolve.  The **[Recurring challenges](./recurring-challenges.md)** identify persistent patterns of difficulty that arise within that environment.  The **[Coverage analysis of existing approaches](./coverage-analysis-of-existing-approaches/index.md)** examined how dominant families of practices distribute governance effort across knowledge objects and governance modes.

The question now is not whether existing approaches are valuable.  They clearly are.  *The question is whether the distribution of governance configurations revealed by the coverage analysis is sufficient to address the recurring challenges of long-lived software systems.*


## From recurring challenges to epistemic governance

The recurring challenges are not homogeneous.  Some are primarily execution-level problems.  Others are structural.  A subset, however, are directly tied to the status of system-level intent as a knowledge object.

In particular, three challenges converge:

- **loss of original intent and rationale over time**,  
- **limited ability to revisit and re-evaluate past decisions**, and  
- **divergence between intent and realized structure**.

These challenges share a common feature: **they arise when system-level purpose, assumptions, and rationale are not maintained as durable, inspectable, and governable knowledge.**

Execution discipline does not solve them.  
Project governance does not solve them.  
Architectural documentation alone does not solve them.

They require sustained epistemic stewardship of intent itself.

If purpose and rationale are only articulated at project initiation, they decay.  
If assumptions are not explicitly preserved, they become implicit.  
If structural evolution is not continuously related back to declared intent, divergence accumulates gradually and often invisibly.

The governance–knowledge matrix introduced in **[Coverage analysis of existing approaches](./coverage-analysis-of-existing-approaches/index.md)** makes this relationship precise.  
The configuration capable of addressing these challenges is **Epistemic × Intentional** governance:

- **Epistemic** — because intent must be treated as inspectable, evolvable knowledge.
- **Intentional** — because the object governed is purpose, assumptions, commitments, and non-goals.

The coverage analysis shows that this configuration is not strongly institutionalized across existing families of approaches.


## Durability as the decisive dimension

Organizations frequently combine methodologies, portfolio frameworks, architecture practices, governance standards, and tool-based documentation systems. This combination improves coordination, alignment, and compliance.

However, combining families does not automatically produce durable epistemic governance of system-level intent.

Software evolution research consistently shows that systems outlive projects and teams ([Lehman & Ramil, 2003](../resources/bibliography.md#lehman-ramil-2003); [Bennett & Rajlich, 2000](../resources/bibliography.md#bennett-rajlich-2000)). Over extended time horizons:

- rationale fragments,
- decision context is lost,
- alignment between declared purpose and realized structure erodes.

Empirical studies of architectural knowledge management further show that documentation and rationale records decay without sustained governance processes ([van der Ven et al., 2006](../resources/bibliography.md#van-der-ven-etal-2006); [Kruchten et al., 2015](../resources/bibliography.md#kruchten-etal-2015)).

This erosion is not primarily a failure of execution.  
It is not primarily a failure of project management.  
It is not primarily a failure of structural modeling.

It is a failure of durable epistemic governance of intent.


## Structural asymmetry revealed by the coverage analysis

The aggregated governance–knowledge matrix in **[Coverage analysis of existing approaches](./coverage-analysis-of-existing-approaches/index.md)** revealed a patterned distribution of governance effort:

- Execution is strongly governed.
- Investment intent is formally governed at managerial levels.
- Structural knowledge is explicitly articulated in architecture-centric approaches.
- Durable epistemic governance of system-level intent is comparatively sparse.

This asymmetry is structural rather than incidental. It reflects how dominant approaches conceptualize what is governable and how governance should be exercised.

Where intent is governed, it is typically framed managerially—through plans, objectives, funding criteria, and compliance constraints—rather than epistemically, as durable and revisitable system-level knowledge.

The recurring challenges most directly tied to long-term system evolution align precisely with this sparsely activated configuration.


## The upstream shift

Upstream Software Engineering does not replace existing families of approaches.  
It redefines what must be treated as governable.

Specifically, it foregrounds:

- explicit articulation of system-level intent as a durable knowledge object,
- traceable linkage between intent and structural decisions,
- institutionalized mechanisms for revisiting assumptions and commitments over time,
- preservation of rationale across organizational and provider transitions.

Its locus of concern is neither execution discipline nor project authorization nor architectural description in isolation.

Its locus is the epistemic stewardship of purpose across evolution.

Upstream Software Engineering therefore addresses a structural asymmetry revealed by the coverage analysis:

While execution, investment intent, and structural articulation are strongly governed,  
durable epistemic governance of system-level intent is not systematically institutionalized.

Making this configuration explicit is the conceptual shift that motivates an upstream discipline.


## Link to scope clarification

The argument presented here does not imply that upstream concerns are absent from existing approaches. Elements of epistemic and intentional governance appear in various families. However, they are not consistently foregrounded as a primary locus of governance.

The next page, **[Scope and non-goals](./scope-and-non-goals.md)**, clarifies what this upstream perspective does and does not attempt to justify.