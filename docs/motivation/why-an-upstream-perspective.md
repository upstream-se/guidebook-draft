# Why an upstream perspective

The **[Problem space](./problem-space.md)** describes the environment in which software systems exist and evolve.  The **[Recurring challenges](./recurring-challenges.md)** identify persistent patterns of difficulty that arise within that environment.  The **[Coverage analysis of existing approaches](./coverage-analysis-of-existing-approaches/index.md)** examined how dominant families of practices distribute governance effort across knowledge objects and governance modes.

The question now is not whether existing approaches are valuable.  They clearly are.  The question is whether the distribution of governance configurations revealed by the coverage analysis is sufficient to address the recurring challenges of long-lived software systems.


## From recurring challenges to epistemic governance

The recurring challenges differ in kind.  Some arise from difficulties in coordinating and executing work.  Others arise from managing structural complexity.  A third category emerges when system-level intent — purpose, assumptions, and guiding rationale — is not treated as something that must be explicitly preserved over time.

The following challenges belong to this third category:

- loss of original intent and rationale over time,  
- limited ability to revisit and re-evaluate past decisions, and  
- divergence between intent and realized structure.

These challenges share a common feature: **they arise when system-level purpose, assumptions, and rationale are not maintained as durable, inspectable, and governable knowledge.**

Methodologies and process frameworks strengthen coordination and responsiveness in ongoing work, but they do not by themselves institutionalize durable stewardship of system-level intent.  

Project and portfolio management approaches articulate objectives, investment criteria, and strategic alignment, yet these mechanisms are typically bounded by initiative lifecycles rather than sustained across the long-term evolution of the software system.  

Architecture-centric approaches make structural knowledge explicit and inspectable, but without sustained epistemic processes focused on system-level purpose, assumptions, and non-goals, rationale and intent tend to erode over time.

Taken together, these families govern activity, investment, and structure effectively within their respective scopes.  What remains comparatively under-institutionalized is the long-term epistemic stewardship of system-level intent across initiatives, teams, and organizational transitions.

When intent is not treated as an explicit knowledge asset, predictable patterns emerge:

- If purpose and rationale are only articulated at project initiation, they decay.  
- If assumptions are not explicitly preserved, they become implicit.  
- If structural evolution is not continuously related back to declared intent, divergence accumulates gradually and often invisibly.

The governance–knowledge matrix introduced in **[Coverage analysis of existing approaches](./coverage-analysis-of-existing-approaches/index.md)** makes this relationship precise.  The configuration capable of directly addressing these challenges is **Epistemic × Intentional** governance:

- **Epistemic** — because intent must be treated as inspectable, evolvable knowledge.
- **Intentional** — because the object governed is purpose, assumptions, commitments, and non-goals.

The coverage analysis shows that this configuration is not strongly institutionalized across existing families of approaches.


## Durability as the decisive dimension

Organizations frequently combine methodologies, portfolio frameworks, architecture practices, governance standards, and tool-based documentation systems.  This combination improves coordination, alignment, structural visibility, and compliance.

Yet combination alone does not guarantee durability.

Software systems outlive projects, roadmaps, and teams.  Software evolution research consistently shows that systems persist and change across extended time horizons ([Lehman & Ramil, 2003](../resources/bibliography.md#lehman-ramil-2003); [Bennett & Rajlich, 2000](../resources/bibliography.md#bennett-rajlich-2000)).  Over time:

- rationale fragments,
- decision context fades,
- assumptions become implicit,
- alignment between declared purpose and realized structure gradually erodes.

Empirical studies of architectural knowledge management further demonstrate that documentation and rationale artifacts decay unless supported by sustained governance processes ([van der Ven et al., 2006](../resources/bibliography.md#van-der-ven-etal-2006); [Kruchten et al., 2015](../resources/bibliography.md#kruchten-etal-2015)).  Making structure explicit is not equivalent to maintaining intent as living knowledge.

More recent empirical research reinforces this durability concern.  Studies of architectural technical debt and architectural drift show that structural decisions degrade under continuous change pressure unless explicitly governed as long-lived knowledge assets ([Li et al., 2015](../resources/bibliography.md#li-etal-2015); [Avgeriou et al., 2016](../resources/bibliography.md#avgeriou-etal-2016)).  Investigations of large-scale agile and DevOps settings further indicate that rapid iteration and decentralized decision-making, while improving responsiveness, can exacerbate loss of architectural rationale and long-term coherence without explicit stewardship mechanisms ([Tamburri et al., 2018](../resources/bibliography.md#tamburri-etal-2018); [Zazworka et al., 2013](../resources/bibliography.md#zazworka-etal-2013)).  These findings extend the classical evolution literature by showing that durability challenges persist even in contemporary development paradigms.

The observed erosion does not primarily stem from weaknesses in execution, project coordination, or architectural modeling taken individually.  Each of these dimensions may be well managed within its scope.

The deeper issue concerns durability.  When system-level intent is not institutionalized as inspectable and revisitable knowledge, it gradually fragments across initiatives, teams, and structural transformations.  What is lacking is not activity, planning, or documentation, but sustained epistemic governance of intent itself.


## Structural asymmetry revealed by the coverage analysis

The aggregated governance–knowledge matrix in **[Coverage analysis of existing approaches](./coverage-analysis-of-existing-approaches/index.md)** reveals not random variation, but a patterned distribution of governance effort:

- Execution is strongly governed.
- Investment intent is formally governed at managerial levels.
- Structural knowledge is explicitly articulated, particularly in architecture-centric approaches.
- Durable epistemic governance of system-level intent remains comparatively sparse.

This asymmetry is structural rather than incidental.  It reflects how dominant approaches define what is legitimately governable and through which modes governance should be exercised.

When intent is governed, it is typically framed managerially—through plans, objectives, funding criteria, and compliance constraints.  These mechanisms make intent visible at moments of authorization and oversight.  They do not, however, systematically institutionalize intent as durable, inspectable, and revisitable knowledge across the long-term evolution of the software system.

The recurring challenges most closely associated with long-lived system evolution—loss of original intent and rationale, limited revisitability of past decisions, and gradual divergence between intent and realized structure—align precisely with this sparsely activated configuration.

The asymmetry therefore concerns not whether governance exists, but where it concentrates and what it leaves comparatively under-institutionalized.


## The upstream shift

Upstream Software Engineering does not replace existing families of approaches.  It rearticulates what must be treated as governable within long-lived software systems.

Specifically, it foregrounds:

- explicit articulation of system-level intent as a durable knowledge object,
- traceable linkage between intent and structural decisions,
- institutionalized mechanisms for revisiting assumptions and commitments over time,
- preservation of rationale across organizational and provider transitions.

Its locus of concern is not execution discipline, project authorization, or architectural description in isolation.  Its locus is the sustained epistemic stewardship of system-level purpose across evolution.

In light of the structural asymmetry identified in the coverage analysis, this shift is not additive but directional.  

Execution is strongly governed.  Investment intent is formally articulated.  Structure is explicitly described.  What remains comparatively under-institutionalized is durable epistemic governance of system-level intent.

Making this configuration explicit — and treating it as a first-class concern — constitutes the conceptual shift that motivates an upstream discipline.


## Scope clarification

The argument developed in this page does not claim that upstream concerns are entirely absent from existing approaches.  pElements of epistemic and intentional governance appear across several families.

The structural observation is narrower: these elements are not systematically institutionalized as a primary locus of governance across long-lived system evolution.

The page **[Scope and non-goals](./scope-and-non-goals.md)** specifies the boundaries of this upstream perspective — what it seeks to establish, and what it does not attempt to replace or subsume.
