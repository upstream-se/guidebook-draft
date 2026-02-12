# Why an upstream perspective

The **[Problem space](./problem-space.md)** and **[Recurring challenges](./recurring-challenges.md)** pages described the environment in which long-lived software systems evolve and the patterns of difficulty that repeatedly arise in practice.  

The **[Coverage analysis of existing approaches](./coverage-analysis-of-existing-approaches/index.md)** then examined how major families of approaches distribute governance effort across knowledge objects and governance modes.

The question that follows from that analysis is not whether governance exists, nor whether existing approaches are valuable. *The question is whether the observed distribution of governance effort across knowledge objects and governance modes is sufficient to address the recurring challenges of long-lived software systems.*

This page articulates why that configuration calls for an upstream perspective.


## From structural asymmetry to conceptual necessity

The aggregated governance–knowledge matrix revealed a patterned distribution:

- Strong governance of execution.
- Strong managerial governance of declared intent.
- Partial governance of structural knowledge.
- Weak activation of epistemic × intentional governance.

This distribution reflects how dominant approaches conceptualize what is governable:

- Execution is governed through discipline and coordination.
- Investments and objectives are governed through managerial oversight.
- Structure is governed through architectural representation and compliance.
- Intent, however, is typically governed only in managerial planning terms, not as durable epistemic knowledge.

The recurring challenges identified in **[Recurring challenges](./recurring-challenges.md)** — particularly:

- loss of original intent and rationale over time,
- divergence between intent and realized structure,
- limited ability to revisit and re-evaluate past decisions —

are structurally linked to this distribution.

If intent is articulated primarily as managerial planning artifact rather than as inspectable and evolvable knowledge, then long-term coherence depends on continuity of individuals, tacit memory, or informal practice. As systems evolve across projects, teams, and organizational transitions, such continuity cannot be assumed.

The structural asymmetry therefore produces predictable fragilities.


## The limits of initiative-bound governance

Project and portfolio frameworks govern initiatives.  
Methodologies govern execution.  
Architecture approaches govern structure.  
Compliance frameworks govern institutional control.  
Tool-centric approaches govern artifacts.

Yet software systems persist beyond individual initiatives and often beyond stable organizational configurations.

Research on software evolution emphasizes that systems continue to change long after their original development context has shifted ([Lehman & Ramil, 2003](./resources/bibliography.md#lehman-ramil-2003); [Bennett & Rajlich, 2000](./resources/bibliography.md#bennett-rajlich-2000)). Governance structures tied primarily to projects, iterations, or compliance cycles do not fully account for this persistent evolution.

When governance is initiative-bound, long-lived system intent becomes vulnerable to:

- reinterpretation without traceability,
- structural drift without explicit comparison to original commitments,
- incremental erosion of rationale.

These patterns correspond directly to the recurring challenges previously identified.


## Toward epistemic governance of system intent

The synthesis in **[Coverage analysis of existing approaches](./coverage-analysis-of-existing-approaches/index.md)** suggests that what is comparatively underrepresented is not additional process, additional documentation, or additional managerial control. Rather, it is sustained epistemic stewardship of system-level intent.

An upstream perspective foregrounds:

- Explicit articulation of system purpose, assumptions, and non-goals.
- Inspectable and revisitable representations of intent.
- Systematic alignment between articulated intent and evolving structure.
- Governance practices that persist across projects, teams, and organizational transitions.

This is not a rejection of existing families. It is a repositioning.

Execution governance remains necessary.  
Managerial oversight remains necessary.  
Architectural reasoning remains necessary.  
Compliance remains necessary.

But without durable epistemic governance of intent, these mechanisms operate without a stable conceptual anchor over long time horizons.


## What “upstream” means in this context

“Upstream” does not mean earlier in time, nor does it refer to front-loaded specification.

It refers to the governance of foundational knowledge that shapes and constrains downstream activity:

- the declared and implicit commitments that give a system its identity,
- the rationale that justifies architectural and strategic decisions,
- the assumptions that frame acceptable change.

Upstream governance concerns the preservation, articulation, and evolution of these elements as inspectable knowledge assets.

In this sense, upstream is not an additional phase.  
It is a distinct locus of governance.


## Logical consequence of the coverage analysis

The need for an upstream perspective is not derived from dissatisfaction with particular methodologies or standards. It follows logically from the structural asymmetry documented in **[Coverage analysis of existing approaches](./coverage-analysis-of-existing-approaches/index.md)**.

If:

- execution is strongly governed,
- investments are strongly governed,
- structure is partially governed,
- but durable epistemic articulation of intent is weak,

then a governance gap exists at the level of system-level intentional knowledge.

The upstream perspective names that gap explicitly and treats it as a primary object of discipline.


## Transition

Having articulated why an upstream perspective is conceptually warranted, the page **[Scope and non-goals](./scope-and-non-goals.md)** clarifies what this motivation does — and does not — claim about existing approaches and about the proposed discipline.
