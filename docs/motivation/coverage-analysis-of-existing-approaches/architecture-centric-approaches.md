# Architecture-centric approaches

Architecture-centric approaches constitute a family of practices concerned with explicitly describing, evaluating, and governing the structural properties of software systems.  They treat architecture as a primary object of attention and provide mechanisms for documenting decisions, reasoning about trade-offs, and maintaining structural coherence over time.

Representative examples of this family include architectural description standards such as [ISO/IEC/IEEE 42010](https://www.iso.org/standard/50508.html), viewpoint-based approaches such as *Views and Beyond* (Clements et al., 2010), evaluation methods such as ATAM developed at the Software Engineering Institute (SEI), Architecture Decision Records (ADRs), reference architectures, the C4 Model, and enterprise-oriented frameworks such as TOGAF.  While differing in scope and formalism, these approaches share a common commitment to making structural knowledge explicit and inspectable.


## Characteristic orientation

Approaches in this family are primarily oriented toward governing the *structure* of software systems.  Their central concern is the organization of components, interfaces, dependencies, and architectural decisions that shape system behavior and quality attributes.

Architectural description standards formalize the identification of stakeholders, concerns, and viewpoints (ISO/IEC/IEEE 42010).  SEI’s architecture-centric methods emphasize systematic evaluation of architectural trade-offs, quality attribute scenarios, and risk identification through structured reasoning processes (Clements et al., 2010).  Architectural knowledge management research further highlights the importance of capturing design decisions and rationale as durable knowledge assets (Kruchten et al., 2015).

Across these variations, architecture is treated not merely as emergent structure, but as an explicit and reasoned representation subject to evaluation, review, and revision.


## Governance mode emphasis

Analyzed through the governance–knowledge lens, architecture-centric approaches frequently emphasize **epistemic governance** of structural knowledge.

They make architectural representations explicit, inspectable, and evolvable.  Decision rationale, trade-offs, and constraints are articulated in forms that can be debated, reviewed, and preserved over time (Perry & Wolf, 1992; van der Ven et al., 2006).  SEI’s evaluation frameworks institutionalize architectural reasoning as a structured, knowledge-based activity rather than as an informal design exercise (Clements et al., 2010).

In many organizational contexts, architecture governance also includes **managerial governance** components, such as architecture review boards, approval gates, or compliance checks.  However, the distinctive contribution of this family lies in treating structural knowledge itself as a governable asset.


## Primary knowledge object governed

The primary knowledge object governed by architecture-centric approaches is **structural knowledge**.

These approaches explicitly regulate how the system is decomposed, how responsibilities are allocated, and how architectural constraints are articulated and preserved.  They address concerns related to modularity, coupling, scalability, performance, and other quality attributes.

Intentional knowledge—such as the broader purpose of the system, long-term strategic commitments, or non-goals—may be referenced in architectural documentation, but it is typically treated as contextual input rather than as a primary object of governance.

Execution practices are also influenced by architecture, but day-to-day workflow discipline is not the central focus of this family.


## Resulting governance configuration

Taken together, architecture-centric approaches tend to cluster around the following governance configurations within the governance–knowledge matrix:

- **Epistemic × Structural** — governance enacted through explicit architectural models, viewpoints, decisions, and evaluation methods.
- **Managerial × Structural** — governance expressed through architecture boards, review processes, and compliance mechanisms.

Occasional movement toward **Epistemic × Execution** may occur when architectural principles are codified into engineering standards or quality attribute guidelines.  However, intentional knowledge is not typically governed as a first-class epistemic object within this family.

This configuration reflects a strong emphasis on structural coherence and architectural reasoning, with comparatively limited systematic focus on durable articulation of system-level intent.


## Relationship to the upstream problem space

Architecture-centric approaches directly address challenges related to structural coherence and divergence between intent and realized structure.  By making architectural decisions explicit and inspectable, they mitigate uncontrolled erosion and enable systematic evaluation of trade-offs (de Silva & Balasubramaniam, 2012; Capilla et al., 2016).

They also partially address decision opacity by documenting architectural rationale (van der Ven et al., 2006).  However, challenges such as loss of original intent over time, fragmentation of system understanding across organizational boundaries, and long-term governance of evolving assumptions extend beyond the structural focus of most architecture frameworks (Lehman & Ramil, 2003).

This observation does not diminish the importance of architectural governance.  Rather, it clarifies that while structural knowledge is treated epistemically, intentional knowledge is not typically governed with the same level of systematic articulation and durability.


## Coverage of recurring challenges

The following table summarizes how architecture-centric approaches typically address the recurring challenges identified in the upstream problem space.

| Recurring Challenge | Typical Coverage | Rationale |
|---------------------|------------------|-----------|
| implicit and unexamined decisions | Medium–High | Architectural decision records, evaluation methods, and formal reviews increase explicit articulation of structural decisions. |
| loss of original intent and rationale over time | Medium | Structural rationale may be documented, but broader system-level intent and non-goals are not always preserved as durable knowledge assets. |
| fragmentation of understanding of the software system | Medium–High | Architectural models and viewpoints provide shared representations that improve system-wide understanding. |
| divergence between intent and realized structure | High | Architecture governance directly targets structural coherence and alignment with quality attribute goals. |
| difficulty assessing and governing change | Medium | Architectural evaluations and impact analyses support reasoned change, though often focused on structural impact. |
| limited ability to revisit and re-evaluate past decisions | Medium–High | Explicit decision documentation enables revisiting structural choices, but systematic re-evaluation of intent remains limited. |


## Transition

Architecture-centric approaches demonstrate how structural knowledge can be governed explicitly and epistemically.  The following pages extend the analysis to governance and compliance frameworks, which emphasize formal oversight and institutional control across organizational contexts.